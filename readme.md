# To Install docker-machine
  curl -L https://github.com/docker/machine/releases/download/v0.16.0/docker-machine-$(uname -s)-$(uname -m) >/tmp/docker-machine &&
  sudo mv /tmp/docker-machine /usr/local/bin/docker-machine &&
  chmod +x /usr/local/bin/docker-machine

## Video use to develop the POC
https://www.youtube.com/watch?v=kqBCHYf_adA&t=381s

## Video used to install docker-machine
https://www.youtube.com/watch?v=nla5LFm46wI

### To create a docker-machine
docker-machine create --driver amazonec2 < name of instance >

### To create the env
docker-machine env < name of instance >

### To eval docker to run on ec2 instance
eval $(docker-machine env < name of instance >)

