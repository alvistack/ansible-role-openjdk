# Ansible Role for Java

## 2.1.0 - TBC

### Major Changes

  - CI with ansible-lint and galaxy-lint-rules
  - Create `/etc/profile.d/java.sh` with templates
  - Source environment variables with `su -l -s /bin/bash -c`
  - Use shell only when shell functionality is required
  - Replace tests from Docker to LXD

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