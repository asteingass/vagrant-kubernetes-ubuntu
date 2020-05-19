# Vagrant Kubernetes Lab based on Ubuntu
initially cloned from: https://bitbucket.org/exxsyseng/k8s_ubuntu/src/master/

## Start
Just run `vagrant up` inside the folder. Thil will create one master and two worker nodes automatically. Once startup finished connect to the master node via `vagrant ssh kmaster`.
Have fun.

## OPTIONAL: Update /etc/hosts
Use the script `sudo ./add_hosts_local.sh` to map the Kubernetes IP with a more usabal hostname
- kmaster.io
- kworker1.io
- kworker2.io
