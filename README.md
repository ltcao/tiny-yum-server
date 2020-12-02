# tiny-yum-server
an ansible playbook to create a tiny yum server (in those cases you need to run on a closed private network ;)

## Installation
1. modify the `inventory/inventory.ini`
2. ensure sane ansible environment before running:
   ```
   # ansible-playbook main.yml --inventory inventory/inventory.ini
   ```
