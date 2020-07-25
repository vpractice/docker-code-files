FROM alpine
LABEL maintainer="kashif@vpractice.pk"
RUN apk add --update nodejs nodejs-npm
COPY . /src
WORKDIR /src
RUN npm install
ENV CREATEDBY="Kashif Bhatti"
EXPOSE 8080
ENTRYPOINT ["node", "./app.js"]
