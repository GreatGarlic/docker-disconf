FROM maven:3.3-jdk-7
MAINTAINER Xusheng Gong <gongxsh00@163.com>
ENV REFRESHED_AT 2016-01-24
ENV ONLINE_CONFIG_PATH /home/work/dsp/disconf-rd/online-resources
ENV WAR_ROOT_PATH /home/work/dsp/disconf-rd/working/war
VOLUME /home/work/dsp/disconf-rd/online-resources
VOLUME /home/work/dsp/disconf-rd/working
WORKDIR /disconf/disconf-web
CMD ["sh", "deploy/deploy.sh"]
