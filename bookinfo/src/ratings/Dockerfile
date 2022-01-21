FROM node:12.18.1-slim 
RUN apt-get update

RUN cp ./package.json /opt/microservices
RUN cp ./ratings.js /opt/microservices
ENV SERVICE_VERSION=v1
RUN npm install  
EXPOSE 9080

CMD ["node", "ratings.js","9080"]
