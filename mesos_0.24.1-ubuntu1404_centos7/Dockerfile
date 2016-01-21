FROM busybox
MAINTAINER PoeZhang <bozhang@thoughtworks.com>

ADD http://downloads.mesosphere.io/master/ubuntu/14.04/mesos_0.24.1-0.2.35.ubuntu1404_amd64.deb /opt/stores/mesos.deb
ADD http://downloads.mesosphere.io/master/centos/7/mesos-0.24.1-0.2.35.centos701406.x86_64.rpm /opt/stores/mesos.rpm

VOLUME /stores

CMD cp -fr /opt/stores/* /stores
