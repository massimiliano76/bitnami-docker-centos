FROM tompizmor/centos-extras:7

ENV PATH="/opt/bitnami/git/bin:$PATH"

RUN yum install -y pkgconfig unzip git
RUN yum groupinstall -y "Development Tools"
# TO DO: build git module for centos and stop installing git from repositories
# RUN bitnami-pkg install git-2.14.1-0 --checksum 6c7935c7f028ab8e8ea38ffab8269b57d87b69b31aae0fc3af8a496e76d0e9cc
