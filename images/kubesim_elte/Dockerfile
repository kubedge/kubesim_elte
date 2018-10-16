FROM scratch
ADD kubesim_elte/ca-certificates.crt /etc/ssl/certs/
ADD kubesim_elte/goclient /goclient
EXPOSE 8080
CMD ["/goclient"]
