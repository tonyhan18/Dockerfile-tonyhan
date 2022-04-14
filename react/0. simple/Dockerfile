FROM node:16-alpine
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY . ./
RUN npm install --silent
RUN npm install react-scripts@5.0.0 -g --silent
RUN npm run build