FROM alpine

COPY ./cn1/entrypoint.sh ./entrypoint.sh

COPY ./cn1/custom_health_check.sh /usr/local/bin/custom_health_check.sh 
  
RUN chmod +x "/usr/local/bin/custom_health_check.sh"

ENTRYPOINT ["/bin/sh", "entrypoint.sh"]
