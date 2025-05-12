FROM alpine:latest
MAINTAINER luckydonald

# docker run -p 8080:8080 --net music_stack --name=ympd -d alpine-ympd:dev
RUN apk --update add ympd


EXPOSE 8080

CMD ["ympd", "-h", "mpd", "-p", "6600", "-w", "8080"]
