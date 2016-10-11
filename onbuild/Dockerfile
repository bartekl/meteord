FROM abernix/meteord:base
MAINTAINER Bartlomiej Leszak

ONBUILD COPY ./ /app
ONBUILD RUN bash $METEORD_DIR/on_build.sh
