# Ansible for Redmine (on CentOS)

## 0. install Ansible

```
$ sudo yum install epel-release
$ sudo yum install ansible
```

## 1. run Ansible

### 1-1. for local install

```
$ git clone https://github.com/douhashi/ansible-redmine-centos.git
$ cd ansible-redmine-centos
$ ansible-playbook -i local site.yml --connection local
```
