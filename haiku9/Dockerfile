FROM node:6

LABEL maintainer "Michael R. Fleet <f1337.us>"

RUN npm install -g haiku9 --quiet

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

EXPOSE 1337

ENV PATH="node_modules/.bin:$PATH"

ENTRYPOINT ["h9"]
CMD ["--help"]
