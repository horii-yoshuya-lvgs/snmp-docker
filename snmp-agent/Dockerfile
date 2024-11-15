FROM	debian:12.7

WORKDIR	/app

RUN	apt update && \
	apt install -y vim systemctl iproute2 && \
	apt install -y snmpd

COPY	bashrc_sample	/root/.bashrc
COPY	snmpd_sample.conf	/etc/snmp/snmpd.conf
