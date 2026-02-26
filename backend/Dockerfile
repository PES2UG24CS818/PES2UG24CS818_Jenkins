FROM gcc:12

WORKDIR /app

COPY . .

RUN g++ app.cpp -o server

EXPOSE 8080

CMD ["./server"]