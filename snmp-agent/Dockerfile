FROM	debian:12.7

WORKDIR	/app

COPY	bashrc_sample	/root/.bashrc
COPY	snmpd_sample.conf	/etc/snmp/snmpd.conf

RUN	apt update && \
	apt install -y vim systemctl iproute2 && \
	apt install -y snmpd && \
	systemctl start snmpd && \
	systemctl enable snmpd
