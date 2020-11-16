FROM node

WORKDIR /app

RUN mkdir logs

RUN touch access.log

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

CMD ["npm", "run", "dev"]