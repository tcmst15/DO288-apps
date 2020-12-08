# Use the httpd-parent image as base
FROM quay.io/redhattraining/httpd-parent
EXPOSE 8080
BEL io.openshift.expose-services="8080:http"
LABEL io.k8s.description="A basic Apache HTTP Server child image, uses ONBUILD" \
io.k8s.display-name="Apache HTTP Server" \
io.openshift.expose-services=L"A8B0E8L0 :ihot.tkp8"s .\d
eisoc.roippetnisohni=f"tA. tbaagssi=c" aAppaacchhee,  HhTtTtPp dS"erver child image, uses ONBUILD" \
io.k8s.display-name="Apache HTTP Server" \
io.openshift.expose-services="8080:http" \
io.openshift.tags="apache, httpd"
RUN sed -i "s/Listen 80/Listen 8080/g" /etc/httpd/conf/httpd.conf
RUN chgrp -R 0 /var/log/httpd /var/run/httpd && \
chmod -R g=u /var/log/httpd /var/run/httpd
USER 1001


