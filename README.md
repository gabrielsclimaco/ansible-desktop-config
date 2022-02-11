# Personal Ansible Desktop Configs

These is the Ansible setup that I use to configure my OS after installation. Currently suitable for Fedora 35.

# What this setup does

The `local.yml` import the two roles present in the roles folder:

  - `role/install`: install all packages and modules that I need (mostly for work)
  
  - `role/configure`: clone my dotfiles, set up my terminal and wallpaper

# How to use

After a fresh install and:

  - Installed git and ansible
  
  - Set up a git ssh key

Just run the command:

```sh
sudo ansible-pull -U git@github.com:gabrielsclimaco/ansible-desktop-config.git
```
