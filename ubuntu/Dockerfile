FROM ubuntu:trusty

# Install.
RUN \
  sed -i 's/# \(.*multiverse$\)/\1/g' /etc/apt/sources.list && \
  apt-get update && \
  apt-get install -y curl git man unzip wget && \
  apt-get install -y make automake gcc g++ cmake sshpass
