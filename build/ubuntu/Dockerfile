FROM ubuntu
RUN echo deb http://mirrors.aliyun.com/ubuntu/ xenial main restricted > /etc/apt/sources.list \
	&& echo deb-src http://mirrors.aliyun.com/ubuntu/ xenial main restricted >> /etc/apt/sources.list \
    && apt-get update \
    && apt-get install -y wget \
    && rm -rf /var/lib/apt/lists/*
