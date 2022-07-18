# Web infrastructure desing

In this project, we will develop a website infraestructure.
Website Infrastructure means the servers, networks, and other underlying infrastructure supporting the Website.

## Resources

* Network basics concept page
* Server concept page
* Web server concept page
* DNS concept page
* Load balancer concept page
* Monitoring concept page
* What is a database
* What’s the difference between a web server and an app server?
* DNS record types
* Single point of failure
* How to avoid downtime when deploying new code
* High availability cluster (active-active/active-passive)
* What is HTTPS
* What is a firewall


## Tasks :page_with_curl:

* **0. Simple web stack**
  Design a one server web infrastructure that hosts the website that is reachable via www.foobar.com
 **REQUIREMENTS:
  * 1 server
  * 1 web server (Nginx)
  * 1 application server
  * 1 application files (your code base)
  * 1 database (MySQL)
  * 1 domain name foobar.com configured with a www record that points to your server IP 8.8.8.8
* **1. Distributed web infrastructure**
  **REQUIREMENTS:
  * 2 server
  * 1 web server (Nginx)
  * 1 application server
  * 1 load-balance (HAproxy)
  * 1 application files (your code base)
  * 1 database (MySQL)

* **2. Secured and monitored web infrastructure **
 ** REQUIREMENTS:
  * 3 firewalls
  * 1 SSL certificate to serve www.foobar.com over HTTPS
  * 3 monitoring clients (data collector for Sumologic or other monitoring services)
