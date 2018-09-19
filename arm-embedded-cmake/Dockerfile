FROM ubuntu:latest

RUN apt-get update && apt-get -y install \
 	build-essential \
 	cmake \
 	git \
	software-properties-common \
	&& add-apt-repository ppa:team-gcc-arm-embedded/ppa -y \
	&& apt-get update \
	&& apt-get install -y gcc-arm-embedded
