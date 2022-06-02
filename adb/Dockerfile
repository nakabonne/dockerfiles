FROM ubuntu:20.04

RUN apt -y update && \
    apt -y upgrade && \
    apt -y install android-tools-adb && \
    apt -y install usbutils

CMD ["adb", "start-server"]
