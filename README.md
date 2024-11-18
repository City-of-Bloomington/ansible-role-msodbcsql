# MS SQL Server Driver for Linux
Ansible Role for maintaing MS SQL server driver on Ubuntu

## Dependencies
- City-of-Bloomington.linux

Example Playbook
----------------

```yml
- hosts: msodbcsql
  become: yes
  roles:
    - City-of-Bloomington.msodbcsql
```

Copying and License
-------
This material is copyright 2016-2017 City of Bloomington, Indiana
It is open and licensed under the GNU General Public License (GPL) v3.0 whose full text may be found at:
https://www.gnu.org/licenses/gpl.txt
