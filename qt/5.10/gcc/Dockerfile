FROM gorzechowski/gcc:xenial

RUN add-apt-repository -y ppa:beineri/opt-qt-5.10.1-xenial

RUN apt-get update && apt-get -y install \
    qt510base \
    qt510websockets

RUN echo "source /opt/qt510/bin/qt510-env.sh" >> /etc/profile
RUN echo "export QMAKESPEC=/opt/qt510/mkspecs/linux-g++" >> /etc/profile
