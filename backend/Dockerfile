FROM node 

WORKDIR /usr/share/app

COPY package*json .

RUN npm i

COPY . .

EXPOSE 1200

CMD ["npm", "start"]

