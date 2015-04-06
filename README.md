# munin-plugin-sysctl

Various munin plugins for sysctl parameters

To install, git clone this project and create symlink in /etc/munin/plugins to various plugin scripts (like vm_dirty) inside the git root directory. 

## vm_dirty

Monitors current dirty memory parameters (sysctl -a | grep dirty).


