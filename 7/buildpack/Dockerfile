FROM bitnami/centos:7

ENV PATH="/opt/bitnami/git/bin:$PATH"

RUN yum install -y pkgconfig unzip perl-devel
RUN yum groupinstall -y "Development Tools"
RUN bitnami-pkg install git-2.14.1-0 --checksum 94e354af83b566a133744f9540241f95f1e45e320743e4458faf61ab92c2c4ec
