FROM node:12

#actual dir doesn't amtter linux file sustem
# we will copy it into a directory called app
# everything inside listening service goes inside app
COPY . /opt/app 

# sets working directiry for any subsequent commands
WORKDIR /opt/app

RUN npm install
CMD npm run watch