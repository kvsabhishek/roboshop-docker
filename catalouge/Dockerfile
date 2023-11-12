FROM node

EXPOSE 8080
WORKDIR /opt/server
COPY . .
RUN npm install
ENV MONGO=true
CMD ["node", "server.js"]