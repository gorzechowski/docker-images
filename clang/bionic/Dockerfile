FROM ubuntu:bionic

RUN apt-get update && apt-get -y install software-properties-common

RUN apt-get update && apt-get -y --allow-unauthenticated install \
    clang-6.0 \
    make \
    cmake \
    subversion

RUN ln -sf /usr/bin/clang++-6.0 /usr/bin/clang++ && ln -sf /usr/bin/clang-6.0 /usr/bin/clang
