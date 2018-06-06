FROM mhart/alpine-node:10.3.0

RUN apk update && apk add --no-cache git

RUN npm install -g pkg

CMD ["/usr/local/bin/pkg", "-t", "node10-alpine-x64", "/app/", "-o", "/app/app.bin"]
