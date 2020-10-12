FROM debian

RUN apt update
RUN apt install -y build-essential
RUN mkdir -p /app
COPY main.c /app
RUN gcc /app/main.c -o /app/app.exe
