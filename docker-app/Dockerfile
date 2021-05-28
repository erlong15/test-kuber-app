FROM ruby:alpine3.13
USER guest
COPY http_server /app
WORKDIR /app
EXPOSE 80
ENTRYPOINT ["ruby", "http_server.rb"]
