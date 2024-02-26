# Containerfiles
Containerfiles for Ymir. Files are built when pulled via Ansible.

# Ymir
Ymir is our production envirnment. When rolling out ansible plays, it will pull any specified image from here and build it on the machines.
After which it will be put into production.

# Development
I strongly recomend you use Vagrant and development branches when developing the playbooks and containerfiles; So that untested and potentionally unstable config is not pushed to prod.
