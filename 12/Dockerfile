FROM node:erbium-alpine@sha256:6a0fa47a0c87853c53d1403b34c79befef7df04902d4e206cfaf6a43bedce0dd
LABEL upstream-maintainer "Tim Brust <tim.brust@sinnerschrader.com>"
LABEL maintainer "Jonathan Egbert<jegbert.eggy@gmail.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --no-cache \
  abuild \
  binutils \
  build-base \
  cmake \
  extra-cmake-modules \
  gcc \
  python2 \
  python3

