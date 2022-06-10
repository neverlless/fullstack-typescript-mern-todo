FROM node

WORKDIR /client

COPY package.json .

RUN npm install\
    && npm install typescript -g

COPY . .

EXPOSE 3000
#RUN yarn install
#RUN yarn start

CMD ["yarn", "start"]

