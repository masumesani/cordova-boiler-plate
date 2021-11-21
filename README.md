# Add cordova platform

If you want to develop for android

`cordova platform add android`

# Get docker image

instead of installing all the dependencies, we'll use docker image

`docker pull beevelop/cordova:latest`

to run docker image and mount current directory and open the bash, navigate to project folder and run this in cmd

`docker run -it -v ${PWD}:/usr/src/project beevelop/cordova bash`

inside docker's bash

`cd /usr/src/project/`

`cordova build android`
