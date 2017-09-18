Ansible Role for Java
=====================

[![Build Status](https://travis-ci.org/alvistack/ansible-role-java.svg?branch=master)](https://travis-ci.org/alvistack/ansible-role-java)
[![GitHub tag](https://img.shields.io/github/tag/alvistack/ansible-role-java.svg)](https://github.com/alvistack/ansible-role-java)
[![GitHub license](https://img.shields.io/github/license/alvistack/ansible-role-java.svg)](https://github.com/alvistack/ansible-role-java/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/galaxy-alvistack.java-blue.svg)](https://galaxy.ansible.com/alvistack/java)

Ansible Role for Oracle Java Installation.

Requirements
------------

This role require Ansible 2.3 or higher.

This role was designed for Ubuntu 16.04/14.04 or CentOS 7/6.

Role Variables
--------------

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th>parameter</th>
<th>required</th>
<th>default</th>
<th>choices</th>
<th>comments</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>java_url</td>
<td>no</td>
<td><code>http://download.oracle.com/otn-pub/java/jdk/8u144-b01/090f390dda5b47b9b721c7dfaa008135/jre-8u144-linux-x64.rpm</code></td>
<td></td>
<td>URL for download Oracle JRE RPM</td>
</tr>
</tbody>
</table>

Dependencies
------------

No additional role dependencies.

Example Playbook
----------------

    - hosts: all
      roles:
        - role: java

License
-------

-   Code released under [Apache License 2.0](https://github.com/alvistack/ansible-role-java/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

Author Information
------------------

-   Wong Hoi Sing Edison
    -   <https://twitter.com/hswong3i>
    -   <https://github.com/hswong3i>

