FROM arm32v7/debian:latest
ENV LC_ALL=C
RUN apt-get -y update && apt-get install -y dovecot-core dovecot-imapd dovecot-ldap dovecot-lmtpd
VOLUME [/etc/dovecot /srv/mail]
CMD ["/usr/sbin/dovecot", "-F"]
