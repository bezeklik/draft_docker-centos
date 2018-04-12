FROM centos:7

LABEL maintainer "Bezeklik"

RUN yum --assumeyes remove \
        alsa-* \
        iwl*-firmware \
        aic94xx-firmware \
        ivtv-firmware \
        linux-firmware \
        NetworkManager-{tui,wifi} \
        teamd && \
    sed -i '/^GSSAPIAuthentication/ s/^/#/' /etc/ssh/sshd_config && \
    sed -i '/^X11Forwarding/ s/^/#/' /etc/ssh/sshd_config && \
    sed -e '/installonly_limit/ s/5/0/' -i /etc/yum.conf

CMD ["/bin/bash"]
