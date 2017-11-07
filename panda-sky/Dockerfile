FROM node:6

LABEL maintainer "Michael R. Fleet <https://github.com/f1337>"

RUN apt-get update \
  && apt-get install -y zip

RUN npm install -g panda-sky --quiet

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

ENV PATH="node_modules/.bin:$PATH"

ENTRYPOINT ["sky"]
CMD ["--help"]
