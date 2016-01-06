
# Mesos installing packages docker storage

## Usage

~~~~~~
docker --rm -v /tmp:/stores k8smesos/mesos-pack:$TAG
# ubuntu
sudo dpkg -i /tmp/mesos.deb
sudo apt-get install -f
~~~~~~
