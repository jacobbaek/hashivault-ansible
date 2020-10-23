# Make the environment that can access ssh server via vault
This playbook assumed that vault service already run.

# Ansible roles and host group
* vault server : vault real server
* vault test server : ssh target server
* vault test client : ssh client

# Keep to know
* Change the remote_user in ansible.cfg

