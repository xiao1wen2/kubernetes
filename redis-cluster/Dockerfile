FROM redis:6.2

RUN apt-get update -y
RUN apt-get install -y  ruby \
rubygems
RUN apt-get clean all
RUN gem install redis
RUN apt-get install dnsutils -y
COPY redis-trib.rb /usr/local/bin/
