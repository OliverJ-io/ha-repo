ARG BUILD_FROM
FROM $BUILD_FROM

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

COPY rootfs /
RUN apk add --no-cache git

RUN chmod a+x /etc/addon/run
CMD [ "/etc/addon/run" ]