# Install and config kubernetes by ansible

## For config ssh

```bash
$ ansible-playbook ./playbooks/config-ssh.yml --ask-pass
# Enter your nodes password
```

## Install kubernetes

```bash
ansible-playbook ./playbooks/install-kubernetes.yml
```
