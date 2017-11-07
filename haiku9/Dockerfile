FROM node:6

LABEL maintainer "Michael R. Fleet <https://github.com/f1337>"

RUN npm install -g haiku9 --quiet

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

EXPOSE 1337

ENV PATH="node_modules/.bin:$PATH"

ENTRYPOINT ["h9"]
CMD ["--help"]
