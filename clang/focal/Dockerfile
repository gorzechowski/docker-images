FROM ubuntu:focal

RUN apt-get update && apt-get -y install software-properties-common

RUN apt-get update && apt-get -y --allow-unauthenticated install \
    clang-9 \
    make \
    cmake

RUN ln -sf /usr/bin/clang++-9.0 /usr/bin/clang++ && ln -sf /usr/bin/clang-9.0 /usr/bin/clang
