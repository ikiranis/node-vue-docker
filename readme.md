# Dev environment with node, vue.js and gridsome

### Install

- Clone this files to your project folder
(Warning: You must create your project inside this folder)

- Run to build the docker image

```
docker-compose build
```

- Run to create the container and login to terminal

```
docker-compose run --rm --service-ports nod_dev_env
```

Or

```
docker exec -ti nod_dev_env_run_1 /bin/bash
```

You are ready to run npm and vue commands, like:

```
vue create myProject
```

```
vue ui -h 0.0.0.0 -p 8086
```

or

```
gridsome develop -h 0.0.0.0 -p 8086
```

Be carefull with the above command. You must run it with host and port parameters to work

```
npm install

npm run serve
```


