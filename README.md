# ansible-kubernetes
Run kubernetes manifests with ansible


# Steps

Install Dependencies
``` 
$ python3 -m venv venv
$ chmod +x ./venv/bin/activate
$ source ./venv/bin/activate
$ pip3 install --upgrade pip
$ pip3 install -r requirement.txt
```

# Execute
```
$ ansible-playbook playbooks/kubernetes.yaml -e host=test-1
```
