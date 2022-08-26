FROM ruby:3-buster

WORKDIR /workdir

COPY ./ ./

RUN bundle install

EXPOSE 9080

CMD ["sh", "-c", "bundle exec rackup -o 0.0.0.0 -p 9080"]
