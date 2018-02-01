FROM rpi-raspbian-base
WORKDIR /build-tmp
RUN apt install python
RUN wget -q http://releases.llvm.org/3.5.2/llvm-3.5.2.src.tar.xz && tar xf llvm-3.5.2.src.tar.xz && mkdir llvm-3.5.2 && cd llvm-3.5.2 && cmake ../llvm-3.5.2.src && cmake --build . && cmake --build . --target install && rm -rf /build-tmp


