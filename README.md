Role Name
=========

- name: upgrade all packages
- name: Install epel
- name: Install yum-cron.
- name: Ensure yum-cron is running and enabled on boot.
- name: Configure autoupdates
- name: Install packages
- name: Install python modules
- name: Ensure fail2ban is running and enabled on boot.
- name: Update SSH configuration to be more secure.
- name: Add configured user accounts to passworded sudoers.
- name: Create user
- name: Upload auth keys
- name: Zsh configuration
- name: Get tmux conf
- name: Get git conf
- name: Get vimrc
- name: Get vundle
- name: Install vim plugins

Role Variables
--------------

No


Example Playbook
----------------

    - hosts: servers
      roles:
         - histrio.settle

License
-------

BSD

Author Information
------------------

Rinat Sabitov (Ринат Сабитов)
rinat.sabitov@gmail.com
4096R/D122293D: 8A98 93D4 B64B 480E 471D BE57 1883 9067 D122 293D

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
