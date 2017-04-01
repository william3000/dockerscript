FROM r-base

# ö
MAINTAINER aa <aa@daocloud.io>


    


# ÅÖĬÈ·ÅÃApp µÄ¿¼
RUN mkdir -p /app  
WORKDIR /app  
EXPOSE 80  
CMD ["bash","-c","while true; do echo begin ; touch /var/log/app.log; tail -f /var/log/app.log; sleep 60; done"]  

