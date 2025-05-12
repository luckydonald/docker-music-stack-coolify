FROM python:3-alpine
MAINTAINER luckydonald

RUN pip install MPD_sima

COPY sima.conf /MPD_sima-$SIMA_VERSION/sima.conf
WORKDIR MPD_sima-$SIMA_VERSION

CMD ["mpd-sima", "-c", "sima.conf"]
