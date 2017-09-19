# ansible-perftest

A dummy role to test variable (and originally include) performance between ansible versions.

simply run with

```
ansible-playbook -i inventory perftest.yml
```

* perftest.yml: using variables from other hosts through hostvars
* perftest2.yml: simple variable usage
