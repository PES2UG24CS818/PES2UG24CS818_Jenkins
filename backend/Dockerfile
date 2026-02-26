FROM ubuntu:22.04

RUN apt-get update || true && \
    apt-get install -y g++ || true

COPY . /app
WORKDIR /app

RUN g++ server.cpp -o server

EXPOSE 8080

CMD ["./server"]