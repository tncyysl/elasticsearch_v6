---
- hosts: google
  remote_user: tuncay
  become: yes
  become_user: root
  roles:
   - ansible-elasticsearch