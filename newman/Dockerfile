#FROM node:alpine

#WORKDIR /newman

#RUN npm install -g newman


#COPY . .
#EXPOSE 3002
#ENTRYPOINT ["json-server","db.json"]
#ENTRYPOINT ["newman"]
#CMD [""]

FROM node:alpine

WORKDIR /newman
RUN npm install -g newman newman-reporter-htmlextra


COPY . .

ENTRYPOINT ["newman"]

