FROM node:16
WORKDIR /workspace
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000 5173
CMD ["npm", "start"]