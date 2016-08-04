macbook-provisioning
====================

A mirror of the Ansible scripts used to provision my Macbook, minus any private stuff.

See http://marvelley.com/blog/2014/04/11/local-provisioning-with-ansible/ for details.

Install Ansible:
$ sudo easy_install pip
$ sudo pip install ansible

Execute with:
ansible-playbook ./playbook.yml -i ./hosts
