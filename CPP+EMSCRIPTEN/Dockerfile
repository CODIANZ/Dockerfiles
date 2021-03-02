FROM ubuntu:18.04
RUN apt-get update \
 && apt-get install -y build-essential gdb cmake git python3 \
 && git clone https://github.com/emscripten-core/emsdk.git \
 && cd emsdk \
 && ./emsdk install latest \
 && ./emsdk activate latest \
 && echo 'source "/emsdk/emsdk_env.sh"' >> $HOME/.bashrc
 