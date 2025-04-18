Simple collections of Ansible playbooks made to utilize a suite of common Linux utilities. Originally made for use at blue team competitions.

TODO:
- Playbook for firewall modifications when already set up
  - ~~Automatic provisioning of firewalld~~
  - ~~Block IP~~
  - ~~Open/close port~~
  - ~~Allow/disallow service~~
  - ~~Fix quarantine system~~
- Backup system
  - Minimal, Mid, and Maximal options for backups
  - FW config backup system
  - Get hashes (for restore)
  - Centralized backup option
  - Option to use distributed redundancy across non-backup machines
- Restore system
  - Anti-tamper using hashes
  - System to prevent restoring to the incorrect machine
- Logging system
  - ~~Automatically deploy Filebeat~~
  - Automatically secure Filebeat -> Logstash/Elasticsearch connection with SSL
  - Automatically deploy Elastic Agent
- Password change system
  - Passwords prebaked into vaults
