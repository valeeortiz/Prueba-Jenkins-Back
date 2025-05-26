FROM node:18-alpine

WORKDIR /project-back-end

COPY ./dist ./dist
COPY package*.json ./

EXPOSE 3000

CMD ["node", "dist/main.js"]