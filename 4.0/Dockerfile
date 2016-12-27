FROM node:alpine

ENV RAML2HTML_VERSION 4.0

RUN npm install --global "raml2html@${RAML2HTML_VERSION}" && \
    npm cache --global clean

RUN mkdir -p /data
VOLUME /data
WORKDIR /data

ENTRYPOINT ["raml2html"]

CMD ["--help"]
