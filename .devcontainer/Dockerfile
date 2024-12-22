# [Choice] Ubuntu version (use jammy or bionic on local arm64/Apple Silicon): jammy, focal, bionic
# ARG VARIANT="focal"
# FROM buildpack-deps:${VARIANT}-curl
FROM ubuntu:24.04

LABEL dev.containers.features="common"
ENV CHROME_BIN=/usr/bin/chromium

# [Optional] Uncomment this section to install additional OS packages.
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
     && apt-get -y install --no-install-recommends nginx tmux


