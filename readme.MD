# Ansible

## Ansible Installation in RHEL

* system updates

```
sudo dnf update -y
```
```
sudo dnf install ansible -y
```

````````````
 ec2-user@ip-172-31-3-93 ~ ]$ ansible --version
ansible [core 2.14.18]
  config file = /etc/ansible/ansible.cfg
  configured module search path = ['/home/ec2-user/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /usr/lib/python3.9/site-packages/ansible
  ansible collection location = /home/ec2-user/.ansible/collections:/usr/share/ansible/collections
  executable location = /usr/bin/ansible
  python version = 3.9.25 (main, Apr 17 2026, 00:00:00) [GCC 11.5.0 20240719 (Red Hat 11.5.0-14)] (/usr/bin/python3)
  jinja version = 3.1.2
  libyaml = True
```````````````