ARG BUILD_FROM
FROM $BUILD_FROM

# Copy root filesystem
COPY rootfs /

# Setup base
RUN apk update && \
    apk upgrade && \
    apk add --no-cache wget python3 py3-pip

## Install required pythpn modules
RUN pip install --upgrade pip && \
    pip install paho-mqtt requests

## Change permissions
RUN chmod +x /app/DahuaVTO.py
RUN chmod +x etc/services.d/dahua/run
RUN chmod +x etc/services.d/dahua/finish
