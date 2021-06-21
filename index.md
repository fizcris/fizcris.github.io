# Personal Portfolio of Cristian Alonso [fizcris]


### [PatatasCamino.com](patastascamino.com)

It is my first full-stack application deployed to production. 
It is a full ERP web application developed with [odoo](https://github.com/odoo/odoo).  
The CI/CD pipeline is based on docker containers and GitHub Actions. Quite simple but straightforward.
It uses different usefull services in the bakedn to keep it secure and updated:
  - [Watchtower](https://github.com/containrrr/watchtower)
  - [Fail2Ban](https://github.com/fail2ban/fail2ban)
  - [Certbot](https://github.com/certbot/certbot)

It also posees a reverse proxy and a work balancer developed with [nginx](https://github.com/nginx/nginx)
Multiple custom plugins were developed extending the database capabilities and improving the UI, open source versions of some of them can be found [here](https://github.com/fizcris/odoo_custom_addons)
