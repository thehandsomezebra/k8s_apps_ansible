# Ansible k8s Playbooks


Load crap up to your cluster with this thing.



```bash
ansible-playbook ./load.yml -i ./inventory/my-cluster/hosts.ini
```


```bash

mkdir ~/.kube
scp ubuntu@192.168.3.38:~/.kube/config ~/.kube/config

kubectl get nodes
#works
```

