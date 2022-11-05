FROM node:alpine
WORKDIR /app/frontend
COPY . . 
RUN npm install
RUN npm run build
EXPOSE 3000
