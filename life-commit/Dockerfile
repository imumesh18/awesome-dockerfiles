FROM alpine:3.7

LABEL maintainer "Umesh Yadav <umesh4257@gmail.com>"

RUN apk --no-cache add \
    git \
    nodejs \
    && npm install -g life-commit

ENTRYPOINT [ "life" ]

CMD [ "help" ]
