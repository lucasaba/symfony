FROM osixia/openldap
ENV LDAP_ORGANISATION="Symfony"
ENV LDAP_DOMAIN="symfony.com"
COPY ./conf/slapd.conf /etc/ldap/slapd.d/slapd.conf
COPY ./data/base.ldif /container/service/slapd/assets/config/bootstrap/ldif/50-base.ldif
COPY ./data/fixtures.ldif /container/service/slapd/assets/config/bootstrap/ldif/50-fixtures.ldif
