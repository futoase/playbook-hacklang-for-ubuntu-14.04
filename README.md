playbook-hacklang-for-ubuntu-14.04
==================================

Ansible playbook of the hacklang(hhvm) for Ubuntu 14.04

Prerequired
------------

- [Ansible](http://www.ansible.com/home)
- [Vagrant](http://www.vagrantup.com/)
- [VirtualBox](https://www.virtualbox.org/)

How to setup?
-------------

```
> vagrant up --provision
> vagrant ssh
> echo '<?hh echo "Hello world\n";' > hello.php
> hhvm hello.php
Hello world
```

LICENSE
-------

MIT.
