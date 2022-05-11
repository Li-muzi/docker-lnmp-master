FROM nginx:1.18

ENV TZ=Asia/Shanghai
ADD sources.list /etc/apt/sources.list
#COPY default.conf /etc/nginx/conf.d/default.conf
COPY official.conf /etc/nginx/conf.d/official.conf
COPY hngaole.cn.conf /etc/nginx/conf.d/hngaole.cn.conf
COPY hunangaole.cn.conf /etc/nginx/conf.d/hunangaole.cn.conf
COPY mmiying.com.conf /etc/nginx/conf.d/mmiying.com.conf
COPY qingzhi.conf /etc/nginx/conf.d/qingzhi.conf
COPY shanin.conf /etc/nginx/conf.d/shanin.conf