ARG VERSION=7.0.15-alpine
FROM redis:${VERSION}

RUN apk update && \
    apk add -y --no-cache tzdata && \
    ln -sf /usr/share/zoneinfo/$TZ /etc/localtime && \
    echo $TZ > /etc/timezone
