# Ansible Role for Java

## 2.3.0 - TBC

### Major Changes

  - Porting test to Molecule based

## 2.2.0 - 2019-01-25

### Major Changes

  - Default install OpenJDK 8 on Ubuntu 16.04 and CentOS 6
  - Default install OpenJDK 11 on Ubuntu 18.04 and CentOS 7
  - Bugfix hardcoded JAVA\_HOME from /etc/profile.d/java.sh

## 2.1.0 - 2018-12-06

### Major Changes

  - CI with yamllint, ansible-lint and ansible-playbook --syntax-check
  - CI with LXD, improve systemd support
  - Use shell only when shell functionality is required
  - Template `/etc/profile.d/java.sh` for environment variables
  - Source environment variables with `su -l -s /bin/bash -c`
  - Default install Oracle Java JRE 8u191-b12
  - Support override with defaults/main.yml

## 2.0.0 - 2018-10-25

### Major Changes

  - Upgrade Ansible support to 2.6 or higher
  - Support both Ubuntu 16.04/18.04 and RHEL/CentOS 6/7
  - Upgrde Jave to 8u191-b12
  - Handle $JAVA\_HOME with /etc/profile.d/java.sh
  - Keep APT/YUM cache as-is
  - Update Travis CI test plan

## 1.1.0 - 2017-11-23

### Major Changes

  - Install Java on Ubuntu 16.04/14.04 from official RPM with alien
  - Install Java on CentOS 7/6 from official RPM
  - Update test cases

## 1.0.0 - 2017-09-25

  - Ininitial release for Ansible 2.4
  - Support both Ubuntu 16.04/14.04 or RHEL/CentOS 7/6
