ARG BUILD_FROM
FROM $BUILD_FROM

COPY run.sh /
RUN chmod a+x /run.sh

COPY detailed_hello_world_push /

CMD [ "/run.sh" ]