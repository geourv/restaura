FROM ruby:3.1

WORKDIR /srv/jekyll

# Install bundler version 1.17.1
RUN gem install bundler -v 1.17.1

COPY Gemfile ./
RUN bundle _1.17.1_ install

CMD [ "bundle", "exec", "jekyll", "serve" ]
