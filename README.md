# ansible.Bootstrap
pull system to usable from fresh install

Requirements:
- SSH & Python

Uses:
    - Create Ansible User
    - admin user -Core Manager
        - ssh key
        - sudoer/wheel status

Manage Connection Perameters
    - ssh key
    - ssh port

Server Security
    - fail2ban
    - firewall

Lockout Root
    - turn off ssh password access to root
    - !!! this will brake Bootstrap from running again. !!!

###################

Ideas
