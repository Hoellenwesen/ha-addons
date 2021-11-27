ARG BUILD_FROM
FROM $BUILD_FROM

# Copy root filesystem
COPY rootfs /

# Setup base
RUN apk update && \
    apk upgrade && \
    apk add --no-cache wget

## Install required pythpn modules
RUN pip install --upgrade pip && \
    pip install paho-mqtt requests

## Get DahuaVTO2MQTT libary
RUN wget https://raw.githubusercontent.com/Hoellenwesen/DahuaVTO2MQTT/master/DahuaVTO.py -P /usr/bin && \
    chmod +x /usr/bin/DahuaVTO.py
