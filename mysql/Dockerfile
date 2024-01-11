FROM debian:bullseye-20231218-slim

RUN apt-get update && \
	apt-get install -y default-mysql-server tzdata && \
    ln -sf /usr/share/zoneinfo/$TZ /etc/localtime && \
    echo $TZ > /etc/timezone && \
	apt-get clean && \
	rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
