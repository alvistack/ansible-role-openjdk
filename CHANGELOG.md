# Ansible Role for OpenJDK

## 4.5.0 - TBC

### Major Changes

  - Remove Ubuntu 19.10 support

## 4.4.0 - 2020-06-04

### Major Changes

  - Support Fedora 32
  - Replace AdoptOpenJDK 13 with 14 for Ubuntu 20.04
  - Install from AdoptOpenJDK repo
  - Support Debian 10
  - `molecule -s default` with delegated to localhost

## 4.3.0 - 2020-04-22

### Major Changes

  - Template `molecule -s default` with dummy docker driver
  - Support CentOS/RHEL 8
  - Support Ubuntu 20.04
  - Remove Ubuntu 16.04 support
  - Upgrade minimal Molecule support to 3.0.2
  - Migrate role name to lowercase or underline
  - Migrate group name to lowercase or underline
  - Migrate molecule `group_vars` to file
  - Add Maven support

## 4.2.0 - 2020-02-13

### Major Changes

  - Migrate molecule driver to Libvirt
  - Migrate molecule verifier to Ansible
  - Support Ubuntu 19.10

## 4.1.0 - 2020-01-16

### Major Changes

  - Default `interpreter_python` with `python3`
  - Bugfix `python3-xml` not exists for openSUSE Leap 15.1
  - Rename role as `openjdk`
  - Add OpenJDK 13 support
  - Add `jshell` for Docker image

## 4.0.0 - 2019-11-05

### Major Changes

  - Upgrade minimal Ansible support to 2.9.0
  - Upgrade Travis CI test as Ubuntu Bionic based

## 3.5.0 - 2019-10-06

### Major Changes

  - Support openSUSE Leap 15.1
  - Default with Python 3
  - Revamp molecule test with vagrant

## 3.4.0 - 2019-09-18

### Major Changes

  - Run molecule test manually on Travis CI
  - Abstract package parameters with multiple version support
  - Support openjdk-11-jdk on Ubuntu 16.04 with PPA

## 3.3.0 - 2019-08-27

### Major Changes

  - Update for RHEL 7
  - Add Vagrant test for RHEL 7

## 3.2.0 - 2019-07-08

### Major Changes

  - Update LXD test profile for Kubernetes v1.15.0 support
  - Fix molecule `group_vars` with links
  - Replace `with_items` with `loop`
  - Replace `with_dict` with `var`
  - Replace `with_first_found` with `lookup('first_found')`

## 3.1.0 - 2019-06-13

### Major Changes

  - Always include default variables from `vars/main.yml`
  - Always use `become: true` with molecule, especially for vagrant

## 3.0.0 - 2019-05-20

### Major Changes

  - Upgrade minimal Ansible support to 2.8.0

## 2.6.0 - 2019-05-04

### Major Changes

  - Refine Travis CI Molecue test cases

## 2.5.0 - 2019-04-17

### Major Changes

  - Run test with `travis_wait 120`

## 2.4.0 - 2019-03-03

### Major Changes

  - Unify variable name as `package`
  - Add openSUSE Leap 15 support
  - Remove CentOS 6 support

## 2.3.0 - 2019-01-30

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
