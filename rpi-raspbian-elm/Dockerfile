FROM rpi-raspbian-cabal
WORKDIR /build-tmp
ENV PATH=$PATH:/root/Elm-Platform/0.18/.cabal-sandbox/bin
RUN curl -sSL https://raw.githubusercontent.com/elm-lang/elm-platform/master/installers/BuildFromSource.hs | sed "s/split-objs: True/split-objs: False/" > BuildFromSource.hs && runhaskell BuildFromSource.hs 0.18

