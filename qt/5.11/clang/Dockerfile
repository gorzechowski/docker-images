FROM gorzechowski/clang:bionic

RUN add-apt-repository -y ppa:beineri/opt-qt-5.11.3-bionic

RUN apt-get update && apt-get -y install \
    qt511base \
    qt511websockets

RUN echo "source /opt/qt511/bin/qt511-env.sh" >> /etc/profile
RUN echo "export QMAKESPEC=/opt/qt511/mkspecs/linux-clang" >> /etc/profile
