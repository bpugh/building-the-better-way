FROM ruby:2.7

ENV LC_ALL C.UTF-8
ENV LANG en_US.UTF-8
ENV LANGUAGE en_US.UTF-8
ENV PAGES_REPO_NWO bpugh/building-the-better-way

WORKDIR /usr/src/app

COPY Gemfile ./
RUN gem install bundler && bundle install

EXPOSE 4000
