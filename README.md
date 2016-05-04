# mydevenv

My development environment by ansible and vagrant.

## Bootstraping

```
$ vagrant up
$ ansible-galaxy install -r roles.yml
$ ansible-playbook site.yml
```

That's it.

## Check connection

```
$ ansible -i hosts -m ping dev
```

