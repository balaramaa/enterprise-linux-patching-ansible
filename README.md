# enterprise-linux-patching-ansible
"Designed for 3500+ servers"
"Reduces patch time by X%"
"Ensures compliance readiness"

# Enterprise Linux Patching (Ansible)

Automated patching workflow for RHEL-based systems.

## Prerequisites
- Ansible 2.11+
- SSH access with sudo privileges
- `yum-utils` (for `needs-restarting` command)

## How to Run
1. Update the `inventory/hosts.yml` with your server list.
2. Run a "Check Mode" (Dry Run) first:
   ```bash
   ansible-playbook site.yml --check

