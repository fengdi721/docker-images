FROM node:16.13.0-alpine

RUN apk update && apk add bash tzdata tree \
    && cp -r -f /usr/share/zoneinfo/Europe/Paris /etc/localtime \
    && apk add --no-cache python3 py3-pip \
    && apk add --update alpine-sdk \
    && apk add libffi-dev openssl-dev \
    && apk add --no-cache --update build-base

WORKDIR /app/src

COPY . .

# RUN yarn install --production
CMD ["tail", "-f", "/dev/null"]