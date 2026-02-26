FROM gcc:12

WORKDIR /app

COPY . .

RUN g++ server.cpp -o server

EXPOSE 8080

CMD ["./server"]