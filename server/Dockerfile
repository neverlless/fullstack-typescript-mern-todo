FROM node

WORKDIR /app

COPY package.json .

RUN npm install\
    && npm install typescript -g

COPY . .

EXPOSE 4000

CMD ["npm","start"]
