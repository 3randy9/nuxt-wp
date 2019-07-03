FROM node:10.15.3-alpine
WORKDIR /myapp
COPY . /myapp

RUN [ -s 'node_modules' ] || yarn

CMD ["yarn", "dev"]
