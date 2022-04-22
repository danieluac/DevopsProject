# DevopsProject


# Cliente ou Host AWS com ssh

```sh
$ ssh -i "rancher-server.pem" ubuntu@ec2-50-17-29-187.compute-1.amazonaws.com         - RancherServer   - HOST A
$ ssh -i "aws-ubuntu-server.pem" ubuntu@ec2-54-235-31-170.compute-1.amazonaws.com     - K8s-1           - HOST B
$ ssh -i "aws-ubuntu-server.pem" ubuntu@ec2-54-221-39-94.compute-1.amazonaws.com      - K8s-2           - HOST C
$ ssh -i "aws-ubuntu-server.pem" ubuntu@ec2-34-235-87-219.compute-1.amazonaws.com     - K8s-2           - HOST D

```
