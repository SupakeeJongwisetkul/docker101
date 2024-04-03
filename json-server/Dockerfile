FROM node:alpine

WORKDIR /app
RUN npm install -g json-server

COPY . .
EXPOSE 3000
#ENTRYPOINT ["json-server","db.json"]
ENTRYPOINT ["json-server"]
CMD ["db2.json"]