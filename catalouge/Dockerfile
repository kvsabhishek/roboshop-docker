FROM node

EXPOSE 8080
WORKDIR /usr/src/app
COPY . .
RUN npm install
ENV MONGO=true
CMD ["node", "server.js"]