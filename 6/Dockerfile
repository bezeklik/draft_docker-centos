FROM centos:6

LABEL maintainer "Bezeklik"

RUN sed -e '/installonly_limit/ s/5/0/' -i /etc/yum.conf

CMD ["/bin/bash"]
