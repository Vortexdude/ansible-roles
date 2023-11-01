### Ansible Roles

1. Install docker
2. Setup the nginx for live streaming server
3. Unknown

##### Run the ansible role in local

``` bash
sudo ansible-playbook configure_nginx.yml -i inventory.yml -c local

```

1. Installing docker via the script

``` bash
wget https://get.docker.com/ -o get-docker.sh 

```

``` bash
wget https://download.docker.com/linux/ubuntu/dists/focal/pool/stable/amd64/containerd.io_1.6.9-1_amd64.deb

wget https://download.docker.com/linux/ubuntu/dists/focal/pool/stable/amd64/docker-ce-cli_20.10.9~3-0~ubuntu-focal_amd64.deb

wget https://download.docker.com/linux/ubuntu/dists/focal/pool/stable/amd64/docker-ce-rootless-extras_20.10.9~3-0~ubuntu-focal_amd64.deb

wget https://download.docker.com/linux/ubuntu/dists/focal/pool/stable/amd64/docker-ce_20.10.9~3-0~ubuntu-focal_amd64.deb

wget https://download.docker.com/linux/ubuntu/dists/focal/pool/stable/amd64/docker-scan-plugin_0.9.0~ubuntu-focal_amd64.deb


```
