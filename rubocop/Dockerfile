FROM ruby:2

LABEL maintainer "Michael R. Fleet <https://github.com/f1337>"

RUN gem install rubocop

ENTRYPOINT ["rubocop"]
CMD ["--help"]
