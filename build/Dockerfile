FROM tomcat:8.5

LABEL maintainer="zhw <coder.zhw@qq.com>"

COPY build/catalina.properties conf/

ENV TZ=Asia/Shanghai

RUN set -x \
    && echo "JAVA_OPTS='-Xms512m -Xmx2048m'" > bin/setenv.sh
