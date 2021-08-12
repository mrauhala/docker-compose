FROM alpine
LABEL maintainer "Mikko Rauhala <mikko@rauhala.net>"

RUN apk add --no-cache tftp-hpa
VOLUME /tftpboot
EXPOSE 69/udp

ENTRYPOINT ["in.tftpd"]
CMD ["--verbose", "--foreground", "--secure", "--create", "--user", "root", "/tftpboot"]
