Playbook
----------------
```yaml
---
- hosts: google
  remote_user: tuncay
  become: yes
  become_user: root
  roles:
   - ansible-elasticsearch-v6
```

https://www.elastic.co/guide/en/elasticsearch/reference/current/important-settings.html
