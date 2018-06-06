FROM mhart/alpine-node:10.3.0

ENV NODE node10
ENV PLATFORM alpine
ENV ARCH x64

RUN apk update
RUN apk add --no-cache git

RUN npm i -g pkg

CMD ["/usr/local/bin/pkg", "-t", "${NODE}-${PLATFORM}-${ARCH}", "/app/", "-o", "/app/app.bin"]
