FROM gorzechowski/clang:bionic

RUN add-apt-repository -y ppa:beineri/opt-qt-5.14.0-bionic

RUN apt-get update && apt-get -y install \
    qt514base \
    qt514websockets

RUN echo "source /opt/qt514/bin/qt514-env.sh" >> /etc/profile
RUN echo "export QMAKESPEC=/opt/qt514/mkspecs/linux-clang" >> /etc/profile
