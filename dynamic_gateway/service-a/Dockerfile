FROM node:22-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install --production
COPY index.js ./
EXPOSE 3001 % (3002 pour service-b)
CMD ["node", "index.js"]