Simple collections of Ansible playbooks made to utilize firewalld. Intended for use at blue team competitions.

TODO:
- Playbook for firewall modifications when already set up
  - Block IP
  - Open/close port
  - Allow/disallow service
  - FW config backup system
- Backup system
  - Minimal, Mid, and Maximal options for backups
  - Get hashes (for restore)
  - Centralized backup option
  - Option to use distributed redundancy across non-backup machines
- Restore system
  - Anti-tamper using hashes
  - System to prevent restoring to the incorrect machine
- Password change system
  - Passwords prebaked into vaults
