FROM rpi-raspbian-ghc
WORKDIR /build-tmp
RUN wget -q https://www.haskell.org/cabal/release/cabal-install-1.22.6.0/cabal-install-1.22.6.0.tar.gz && tar xf cabal-install-1.22.6.0.tar.gz && cd cabal-install-1.22.6.0 && ./bootstrap.sh && rm -rf /build-tmp

ENV PATH=$PATH:/root/.cabal/bin
