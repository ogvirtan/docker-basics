FROM ubuntu:24.04

# Use /usr/src/app as our workdir. The following instructions will be executed in this location.
WORKDIR /usr/src/app

RUN apt-get update && apt-get install -y curl

COPY script.sh .

CMD ["./script.sh"]