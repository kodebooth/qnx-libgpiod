# Copyright (c) 2026 Abe Kohandel
# SPDX-License-Identifier: MIT

FROM ghcr.io/kodebooth/qnx-sdp:latest

ARG VARIANT

RUN apt-get update && apt-get install -y --no-install-recommends \
  meson \
  && rm -rf /var/lib/apt/lists/*
