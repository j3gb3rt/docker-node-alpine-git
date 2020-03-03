FROM node:dubnium-alpine@sha256:b930ae34213b9bcda4ab598d16159cc2acfd5b26342eff536807d99106f4dd84
LABEL upstream-maintainer "Tim Brust <tim.brust@sinnerschrader.com>"
LABEL maintainer "Jonathan Egbert<jegbert.eggy@gmail.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --no-cache \
  # essentials
  bash \
  openssh \
  git \

  # build tools
  abuild \
  binutils \
  build-base \
  cmake \
  extra-cmake-modules \
  gcc \
  python2 \
  python3
