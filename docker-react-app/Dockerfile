FROM node:current-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install

#copy everything from current directory to curent directory in container
COPY . .
# RUN komutu Docker daha image halindeyken çalıştırılır, CMD ise container çalışırken çalıştırılır
CMD ["npm", "start"]