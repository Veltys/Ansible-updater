# Ansible-apt
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/6aa675bb5e4749f885e1b2cbcd01fe51)](https://www.codacy.com/gh/Veltys/Ansible-apt/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Veltys/Ansible-apt&amp;utm_campaign=Badge_Grade)
[![Build Status](https://github.com/Veltys/Ansible-apt/actions/workflows/tester.yml/badge.svg?branch=master)](https://github.com/Veltys/Ansible-apt/actions)
[![GitHub commits](https://badgen.net/github/commits/Veltys/Ansible-apt)](https://GitHub.com/Veltys/Ansible-apt/commit/)
[![GitHub latest commit](https://badgen.net/github/last-commit/Veltys/Ansible-apt)](https://GitHub.com/Veltys/Ansible-apt/commit/)
[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://github.com/Veltys/Ansible-apt/blob/master/LICENSE)

Ansible playbook to update the inventory servers thanks to apt or another equivalent module, as well as other independent programs


## Description
Ansible playbook can be used to update the inventory servers in an automated manner by utilizing the apt or a similar equivalent module, as well as other independent programs that may be necessary to ensure that the servers are fully up to date


## Changelog
### To-do (*TODO*)
- [ ] Create a to-do list

### [1.4.1] - 2023-01-03
#### Fixed
- **apt.yml** header
- New **.gitignore** file

### [1.4.0] - 2023-01-03
#### Added
- *testing* branch

#### Fixed
- **LICENSE** format

#### Removed
- CI data in *master* branch

### [1.3.4] - 2022-12-28
#### Added
- More badges

#### Fixed
- **README.md** format
- Renamed repo

### [1.3.3] - 2022-12-28
#### Fixed
- **README.md** format

### [1.3.2] - 2022-12-27
#### Fixed
- Private key issues

### [1.3.1] - 2022-12-27
#### Added
- GitHub Actions badge
- Private key

### [1.3.0] - 2022-12-27
#### Added
- CI tests

### [1.2.0] - 2022-12-27
#### Added
- Tags

### [1.1.4] - 2022-12-27
#### Added
- Tmux command in Netdata updater task

### [1.1.3] - 2022-12-27
#### Fixed
- Better changelog section in **README.md**
- Better condition to execute Netdata updating task

### [1.1.2] - 2022-12-27
#### Added
- Codacy badge

#### Fixed
- Some cosmetic issues

### [1.1.1] - 2022-12-27
#### Added
- Repo, **LICENSE.MD**, **README.MD** and other files
- Shebang in **apt.yml**

### [1.1.0] - 2022-12-27
#### Added
- Shell module for opkg-based machines

### [1.0.0] - 2022-12-27
#### Added
- Basic playbook **apt.yml**


## Acknowledgments, sources consulted and other credits
* To the [official Ansible documentation](https://docs.ansible.com/ansible/latest/index.html), for obvious reasons