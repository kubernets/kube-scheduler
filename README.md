# kube-scheduler

github addr [https://github.com/kubernets/kube-scheduler](https://github.com/kubernets/kube-scheduler)

docker hub addr [https://hub.docker.com/u/kubernets](https://hub.docker.com/u/kubernets)

use shell script to pull docker image and replace origin tag

> wget https://github.com/kubernets/kube-scheduler/raw/master/get-kube-scheduler-image.sh

## Arch and Version

- [**amd64** v1.11.2](https://hub.docker.com/r/kubernets/kube-scheduler-amd64)

    > docker pull kubernets/kube-scheduler-amd64:v1.11.2

    > docker tag kubernets/kube-scheduler-amd64:v1.11.2 gcr.io/google-containers/kube-scheduler-amd64:v1.11.2 

    > docker rmi kubernets/kube-scheduler-amd64:v1.11.2
