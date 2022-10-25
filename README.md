# ansible-tail
Install Tailscale using Ansible. Successor to [`update-tail`](https://github.com/LLEB-ME/update-tail).

### USAGE
Ensure that you have Tar installed.

1. [Install and configure Ansible.](https://docs.ansible.com/ansible/latest/installation_guide/index.html)
   Optionally, if a device is going to be used as an exit node, add it to both `[hosts]` and `[exit_nodes]`.
2. Clone this repository (`git clone git@github.com:LLEB-ME/ansible-tail.git`)
3. Run this playbook (`ansible-playbook tailscale.yml -bK`)

### ACKNOWLEDGEMENTS
This playbook has not been tested and is not intended for deployment or active usage in the Farer network. This source is not intended to be visible to all members currently. This will change in the future and is planned to be made public.
