# "5" is newer than "5.11"
# https://github.com/CentOS/sig-cloud-instance-images/tree/CentOS-5/docker
# https://github.com/CentOS/sig-cloud-instance-images/tree/CentOS-5.11/docker
FROM centos:5

LABEL maintainer "Bezeklik"

RUN sed -i /etc/yum.repos.d/{CentOS-{Base,fasttrack},libselinux}.repo \
        -e '/^mirrorlist/d' \
        -e '/#baseurl/ s/^#//' \
        -e 's/$releasever/5.11/' \
        -e 's|mirror.centos.org/centos|vault.centos.org|' && \
    yum -y --quiet update && \
    rm -rf /var/cache/yum

CMD ["/bin/bash"]
