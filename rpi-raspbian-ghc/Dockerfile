FROM rpi-raspbian-llvm
WORKDIR /build-tmp
RUN mkdir -p /build && cd /build && wget -q https://downloads.haskell.org/~ghc/7.10.3/ghc-7.10.3-armv7-deb8-linux.tar.xz && tar xf ghc-7.10.3-armv7-deb8-linux.tar.xz && cd ghc-7.10.3 && ./configure && make install && rm -rf /build-tmp

