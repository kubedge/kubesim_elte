FROM scratch
ADD kubesim_elte/ca-certificates.crt /etc/ssl/certs/
ADD kubesim_elte/goserv /goserv
EXPOSE 8080
CMD ["/goserv"]
