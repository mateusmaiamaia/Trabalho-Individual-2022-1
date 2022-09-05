FROM node:13-alpine

WORKDIR /app

ENV PATH /app/node_modules/.bin:$PATH

COPY package.json /app/package.json
COPY ./ ./
RUN npm install 

EXPOSE 3000
CMD ["npm", "start"]