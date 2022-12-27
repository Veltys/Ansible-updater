# ansible-apt
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/6aa675bb5e4749f885e1b2cbcd01fe51)](https://www.codacy.com/gh/Veltys/ansible-apt/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Veltys/ansible-apt&amp;utm_campaign=Badge_Grade)

Ansible playbook to update the inventory servers thanks to apt or another equivalent module, as well as other independent programs


## Description
Ansible playbook can be used to update the inventory servers in an automated manner by utilizing the apt or a similar equivalent module, as well as other independent programs that may be necessary to ensure that the servers are fully up to date


## Changelog
### [1.1.4] - 2022-12-27
#### Added:
- Tmux command in Netdata updater task.

### [1.1.3] - 2022-12-27
#### Fixed:
- Better changelog section in **README.md**.
- Better condition to execute Netdata updating task.

### [1.1.2] - 2022-12-27
- Added Codacy badge.
- Fixed some cosmetic issues.

### [1.1.1] - 2022-12-27
- Repo, **LICENSE.MD**, **README.MD** and other file creation.
- Added shebang in **apt.yml**.

### [1.1.0] - 2022-12-27
- Added shell module for opkg-based machines.

### [1.0.0] - 2022-12-27
- Basic playbook creation **apt.yml**.


## Acknowledgments, sources consulted and other credits
* To the [official Ansible documentation](https://docs.ansible.com/ansible/latest/index.html), for obvious reasons.


## To-do (*TODO*)
- [ ] Create a to-do list
