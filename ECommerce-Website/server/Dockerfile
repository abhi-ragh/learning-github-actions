FROM node:16-alpine
WORKDIR /app
COPY package* /app/
RUN npm install --legacy-peer-deps
COPY . .
EXPOSE 8000
CMD ["npm","start"]