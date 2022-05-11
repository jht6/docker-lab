# https://yeasy.gitbook.io/docker_practice/image/dockerfile/entrypoint
# CMD 与 ENTRYPOINT 的区别
FROM ubuntu:18.04
RUN apt-get update \
  && apt-get install -y curl \
  && rm -rf /var/lib/apt/lists/*
# CMD ["curl", "-s", "http://myip.ipip.net"]
ENTRYPOINT ["curl", "-s", "http://myip.ipip.net"]