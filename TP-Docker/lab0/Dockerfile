# --------------- DÉBUT COUCHE OS -------------------
FROM debian:stable-slim
# --------------- FIN COUCHE OS ---------------------

# MÉTADONNÉES DE L'IMAGE
LABEL maintainer="BTS SIO2 SISR"

# --------------- DÉBUT COUCHE Installation ---------------
RUN apt-get update \
&& apt-get install -y vim git htop mc tree \
&& apt-get clean \
&& rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
# --------------- FIN COUCHE Installation -----------------
