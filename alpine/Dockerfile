FROM registry.cn-hangzhou.aliyuncs.com/tangjunjian/alpine:curl

RUN apk add tzdata && cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
    && echo Asia/Shanghai > /etc/timezone
