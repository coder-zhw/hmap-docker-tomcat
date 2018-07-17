FROM tomcat:8.5

LABEL maintainer="zhw <coder.zhw@qq.com>"

COPY catalina.properties context.xml conf/

ENV TZ=Asia/Shanghai

RUN set -x \
    && echo "JAVA_OPTS='-Xms1024m -Xmx2048m'" > bin/setenv.sh
