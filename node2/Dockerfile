FROM node:latest

RUN mkdir /project

WORKDIR /project

COPY ./project/package.json /project

RUN npm install

EXPOSE 8888

CMD npm start