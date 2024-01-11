ARG VERSION=15.5-alpine
FROM postgres:${VERSION}

RUN apk update && \
    apk add -y --no-cache tzdata && \
    ln -sf /usr/share/zoneinfo/$TZ /etc/localtime && \
    echo $TZ > /etc/timezone
