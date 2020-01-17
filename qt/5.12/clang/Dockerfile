FROM gorzechowski/clang:bionic

RUN add-apt-repository -y ppa:beineri/opt-qt-5.12.6-bionic

RUN apt-get update && apt-get -y install \
    qt512base \
    qt512websockets

RUN echo "source /opt/qt512/bin/qt512-env.sh" >> /etc/profile
RUN echo "export QMAKESPEC=/opt/qt512/mkspecs/linux-clang" >> /etc/profile
