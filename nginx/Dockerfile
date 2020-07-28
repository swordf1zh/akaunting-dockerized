FROM nginx:latest
LABEL maintainer="Ricardo Tribaldos <rtribaldos@barustudio.com>"

RUN echo "START------------------" \
  && adduser -D -H -u 1000 -s /bin/bash www-data -G www-data \

  # BORRAME
  && apt-get update && apt-get install -y procps \
  # BORRAME

  && echo "--------------------END"
