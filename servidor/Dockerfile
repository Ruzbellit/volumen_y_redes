FROM node:15-alpine
WORKDIR /app 
COPY package.json ./
COPY package-lock.json ./ 
RUN npm install 
COPY index.js ./
EXPOSE 5000 
CMD ["npm", "start"]

