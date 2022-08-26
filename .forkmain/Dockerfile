FROM ruby:3-buster

WORKDIR /workdir

COPY ./ ./

RUN bundle install

EXPOSE 9080

CMD ["sh", "-c", "bundle exec ruby details.rb 9080"]
