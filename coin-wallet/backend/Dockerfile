FROM golang:1.18.0
RUN apt-get update && apt-get install -y build-essential make

RUN go install golang.org/x/tools/gopls@latest
RUN go install github.com/ramya-rao-a/go-outline@latest
RUN go install github.com/cosmtrek/air@latest
# RUN wget -O ~/vsls-reqs https://aka.ms/vsls-linux-prereq-script && chmod +x ~/vsls-reqs && ~/vsls-reqs

WORKDIR /backend/src