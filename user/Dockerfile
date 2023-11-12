FROM node:14

EXPOSE 8080
WORKDIR /opt/server
COPY . .

ENV MONGO=true
RUN npm install
CMD ["node", "server.js"]