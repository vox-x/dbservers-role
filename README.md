# dbservers role

An Ansible role to install and configure MariaDB/MySQL on Ubuntu servers for lab and development use.

## 🧰 Features

- Installs `mariadb-server`
- Sets up a custom MySQL user with privileges
- Uses variables for easy password and user control
- Socket-based authentication (secure and simple)
- Idempotent setup with `community.mysql.mysql_user`

---

## 📦 Requirements

- Ansible 2.9+
- Ubuntu 20.04 (focal) or compatible
- Root or sudo access
- `community.mysql` collection installed:

```bash
ansible-galaxy collection install community.mysql

