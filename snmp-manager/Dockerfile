FROM	debian:12.7

WORKDIR	/app

RUN	apt update && \
	apt install -y vim systemctl iproute2 && \
	apt install -y snmp

COPY	bashrc_sample	/root/.bashrc
