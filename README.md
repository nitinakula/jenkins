- name: Jenkins
  hosts: localhost
  roles:
  - { role: ansible-jenkins, become: yes, become_user: root }
