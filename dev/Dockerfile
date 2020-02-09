FROM golang:1.13.7-stretch

WORKDIR /app
COPY ./ /app

RUN go get github.com/githubnemo/CompileDaemon

ENTRYPOINT CompileDaemon --build="go build" --command=/app/mygoapp