FROM node:18-alpine

WORKDIR /project-back-end

COPY package*.json ./
RUN npm install --production

COPY ./dist ./dist

EXPOSE 3000
CMD ["node", "dist/main.js"]