FROM node:12.18.1-slim 
RUN apt-get update

COPY ./package.json /opt/microservices
COPY ./ratings.js /opt/microservices
ENV SERVICE_VERSION=v1
RUN npm install  
EXPOSE 9080

CMD ["node", "ratings.js","9080"]
