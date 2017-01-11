FROM nodered/node-red-docker:latest

USER root

RUN apt-get update && apt-get install -y --no-install-recommends apt-utils
 
RUN apt-get -y install sudo

RUN sudo apt-get -y install libavahi-compat-libdnssd-dev

RUN npm install node-red-contrib-homekit
RUN npm install node-red-node-watson
RUN npm install node-red-contrib-google
RUN npm install node-red-contrib-apiai
RUN npm install node-red-dashboard
RUN npm install node-red-node-email
RUN npm install node-red-contrib-ifttt
RUN npm install node-red-node-darksky
RUN npm install node-red-contrib-wwsNodes
RUN npm install node-red-contrib-alexa-home-skill
RUN npm install node-red-contrib-mock
RUN npm install node-red-node-openweathermap
RUN npm install node-red-contrib-hangouts
RUN npm install node-red-contrib-media-utils

