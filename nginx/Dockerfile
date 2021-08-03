FROM nginx:1.15.2-alpine

ARG timezone=Asia/Shanghai

RUN cp /usr/share/zoneinfo/${timezone} /etc/localtime \
        && echo "${timezone}" > /etc/timezone

CMD ["nginx", "-g", "daemon off;"]