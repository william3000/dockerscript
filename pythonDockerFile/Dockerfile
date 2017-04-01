FROM daocloud.io/ubuntu:trusty

# ö
MAINTAINER aa <aa@daocloud.io>


# APT ×¶¯°²װ PHP Ï¹صÄÀµ°üèËÒ5°üí
RUN apt-get update && \  
      apt-get install -y python \
                       python-dev \
                       python-pip  \
    && apt-get autoclean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* 


# ÅÖĬÈ·ÅÃApp µÄ¿¼
RUN mkdir -p /app  
WORKDIR /app  
EXPOSE 80  
CMD ["bash","-c","while true; do echo begin ; touch /var/log/app.log; tail -f /var/log/app.log; sleep 60; done"]  

