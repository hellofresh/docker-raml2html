FROM node:6.9.2-alpine

RUN npm install -g raml2html@5.0.0 \
 && npm cache clean

RUN mkdir -p /data
VOLUME /data
WORKDIR /data

ENTRYPOINT ["raml2html"]

CMD ["--help"]
