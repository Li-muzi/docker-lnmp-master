FROM nginx:1.18

ENV TZ=Asia/Shanghai
ADD sources.list /etc/apt/sources.list

RUN apt-get update && apt-get install -y \
    vim
#COPY conf/official.conf /etc/nginx/conf.d/official.conf
#COPY conf/hngaojia.conf /etc/nginx/conf.d/hngaole.cn.conf
#COPY conf/hunangaole.cn.conf /etc/nginx/conf.d/hunangaole.cn.conf
#COPY conf/mmiying.com.conf /etc/nginx/conf.d/mmiying.com.conf
#COPY conf/qingzhi.conf /etc/nginx/conf.d/qingzhi.conf
#COPY conf/shanin.conf /etc/nginx/conf.d/shanin.conf