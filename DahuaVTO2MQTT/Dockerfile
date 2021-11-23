ARG BUILD_FROM
FROM $BUILD_FROM

# Copy root filesystem
COPY rootfs /

# Execute during the build of the image
#ARG TEMPIO_VERSION BUILD_ARCH
#RUN \
#    curl -sSLf -o /usr/bin/tempio \
#    "https://github.com/home-assistant/tempio/releases/download/${TEMPIO_VERSION}/tempio_${BUILD_ARCH}"

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
