FROM node:20-alpine

WORKDIR /app

COPY package.json .

COPY . .

RUN npm install
RUN npx prisma generate


EXPOSE 4000

CMD ["npm" , "run" , "start"]