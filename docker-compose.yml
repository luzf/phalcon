FROM luzf/phpfpm

RUN git clone git://github.com/phalcon/cphalcon.git
RUN cd cphalcon/build/ && \
    ./install && \
    cd /tmp && \
    /bin/rm -rf /tmp/cphalcon/