# Dev environment with node and vue.js

### Install

- Clone this files to your project folder

- Run to build the docker image

``
docker-compose build
``

- Run to create the container and login to terminal

``
docker-compose run --rm --service-ports nod_dev_env
``

You are ready to run npm and vue commands, like:

``
vue ui -h 0.0.0.0 -p 8086
``

Be carefull with the above command. You must run it with host and port parameters to work

``
npm install
``

``
npm run serve
``

