FROM debian:latest

MAINTAINER Vladimir Terechov <v1adt3r@gmail.com>
RUN apt-get update && apt-get install -y cowsay fortune
COPY entrypoint.sh /

ENTRYPOINT ["/entrypoint.sh"]