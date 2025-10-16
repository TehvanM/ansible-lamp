# LAMP Stack Ansible Automation

## Author
Jaan Tamm - Student

## Quick Start
1. Update IP in `inventories/production/hosts`
2. Run: `ansible-playbook playbooks/site.yml`
3. Visit: http://your-server-ip

## File Structure
eof
## Test Results
- Apache: ✅ Running on port 80
- MySQL: ✅ Database and user created
- PHP: ✅ Test page working
- Firewall: ✅ Ports 22,80,443 open

![LAMP Stack Screenshot](screenshot.png)
