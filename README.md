# Ansible for Redmine (on CentOS)

## 0. install Ansible

```
$ sudo yum install epel-releas
$ sudo yum install ansible
```

## 1. run Ansible

### 1-1. for local install

```
$ git clone git@github.com:douhashi/ansible-redmine-centos.git
$ cd ansible-redmine-centos
$ ansible-playbook -i local site.yml --connection local
```
