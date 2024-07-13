FROM golang:1.5-alpine
ADD ./kube-scheduler /bin/kube-scheduler
RUN ["chmod", "+x", "/bin/kube-scheduler"]
CMD ["/bin/kube-scheduler"]

