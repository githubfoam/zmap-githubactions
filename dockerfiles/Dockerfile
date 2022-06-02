FROM fedora:latest
LABEL org.opencontainers.image.authors="githubfoam"


RUN set -xe && \
    dnf update -y && \
    yum install zmap -y

ENTRYPOINT ["zmap"]
CMD ["-h"]