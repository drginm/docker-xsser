FROM kalilinux/kali-rolling

WORKDIR /workdir

RUN apt-get update && \
    apt-get install -y xsser

ENTRYPOINT ["xsser"]
