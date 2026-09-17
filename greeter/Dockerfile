FROM ubuntu:24.04

WORKDIR /app

COPY greet .

RUN chmod +x greet

ENV GREETING=aloha
ENV NAME=hoaloha

CMD ["./greet"]
