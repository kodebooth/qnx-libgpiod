# Copyright (c) 2026 Abe Kohandel
# SPDX-License-Identifier: MIT

FROM ghcr.io/kodebooth/qnx-sdp:latest

RUN apt-get update && apt-get install -y --no-install-recommends \
  autoconf \
  autoconf-archive \
  automake \
  build-essential \
  libtool \
  pkg-config \
  && rm -rf /var/lib/apt/lists/*
