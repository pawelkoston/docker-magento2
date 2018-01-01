FROM million12/varnish

MAINTAINER Ash Smith <ash.smith@meanbee.com>

ENV VCL_CONFIG /data/varnish.vcl
ENV VARNISHD_PARAMS -p default_ttl=3600 -p default_grace=3600 -p feature=+esi_ignore_https -p feature=+esi_disable_xml_check -p http_resp_hdr_len=65536 -p http_resp_size=98304

ADD etc/varnish.vcl /data/varnish.vcl
