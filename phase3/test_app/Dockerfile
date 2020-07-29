FROM node:10-alpine
# Following Dockerfile best practices, 
# use WORKDIR to instead of RUN to change directories.
WORKDIR /app
# it's better to use copy than ADD
COPY . /app

RUN npm install

CMD ["npm", "start"]