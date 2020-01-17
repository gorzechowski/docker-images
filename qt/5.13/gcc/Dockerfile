FROM gorzechowski/gcc:bionic

RUN add-apt-repository -y ppa:beineri/opt-qt-5.13.2-bionic

RUN apt-get update && apt-get -y install \
    qt513base \
    qt513websockets

RUN echo "source /opt/qt513/bin/qt513-env.sh" >> /etc/profile
RUN echo "export QMAKESPEC=/opt/qt513/mkspecs/linux-g++" >> /etc/profile
