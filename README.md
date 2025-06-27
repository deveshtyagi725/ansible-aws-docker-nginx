# Ansible + AWS + Docker Project Ì∫Ä

This project provisions an EC2 instance on AWS, installs Docker, and deploys an Nginx container that serves a custom HTML landing page.

## Ì¥ß Steps Performed

1. Created and launched an EC2 Ubuntu instance
2. Opened ports 22 (SSH) and 80 (HTTP) in the security group
3. SSH'd into the instance and installed Docker
4. Ran an Nginx container with a custom `index.html`

## Ì¥ó Live Site

[http://13.49.238.71](http://13.49.238.71)

## Ì≥Å Files

- `index.html`: HTML page served by Nginx
- `docker-run-commands.txt`: Commands used to run the container
- `ec2-setup.md`: Notes on EC2 setup and security group

---
