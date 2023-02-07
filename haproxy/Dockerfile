FROM ubuntu

RUN apt update
RUN apt install -y haproxy
COPY haproxy.cfg /etc/haproxy/haproxy.cfg

EXPOSE 80
CMD ["haproxy", "-f", "/etc/haproxy/haproxy.cfg"]
