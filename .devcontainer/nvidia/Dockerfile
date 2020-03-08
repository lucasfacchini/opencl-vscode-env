FROM nvidia/opencl:runtime-ubuntu18.04
RUN apt-get update \
    && apt-get -y install --no-install-recommends apt-utils dialog 2>&1 \
    && apt-get -y install git iproute2 procps lsb-release \
    && apt-get -y install build-essential cmake cppcheck valgrind ocl-icd-* opencl-headers

CMD ["clinfo"]