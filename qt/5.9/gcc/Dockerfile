FROM gorzechowski/gcc:xenial

RUN add-apt-repository -y ppa:beineri/opt-qt59-xenial

RUN apt-get update && apt-get -y install \
    qt59base \
    qt59websockets

RUN echo "source /opt/qt59/bin/qt59-env.sh" >> /etc/profile
RUN echo "export QMAKESPEC=/opt/qt59/mkspecs/linux-g++" >> /etc/profile
