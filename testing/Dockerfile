# Testing image for phpMyAdmin

FROM alpine:3.21

# Install test dependencies
RUN set -ex; \
	\
	apk add --no-cache --update mariadb-client mariadb-connector-c bash \
	py3-html5lib py3-pytest py3-mechanize curl
