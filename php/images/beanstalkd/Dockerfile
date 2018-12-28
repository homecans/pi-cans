FROM alpine:3.8

LABEL org.label-schema.schema-version="1.0" \
    org.label-schema.name="PHP on alpine" \
    org.label-schema.description="alpine3.8, beanstalkd1.10" \
    org.label-schema.vendor="Duan Li(inputx@goodays.com)" \
    org.label-schema.license="GPLv2" \
    org.label-schema.build-date="20181228"


RUN apk add --update beanstalkd && \
	rm -rf /var/cache/apk/*