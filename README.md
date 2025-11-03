# prepare-debilan

Prepares debilan machines for Kubernetes.

## How to use this?

Start with hardening and copying our ssh keys (comma is necessary, root password is in bitwarden):

```
ansible-playbook -i 192.168.5.11, ssh.yaml -u root --ask-vault-pass
```

After this, you can prepare the machine to run in 