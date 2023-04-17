### Firewall
## Resources
# Read or watch:
* <a href="https://en.wikipedia.org/wiki/Firewall_%28computing%29">What is a firewall</a>

In this project, I used ufw to configure firewalls on my issued web servers.

Resources
UFW - Uncomplicated Firewall
How to Install Firewalld on Linux
Install ufw on Ubuntu: sudo apt-get install ufw
Tasks 📃
0. Block all incoming traffic but

0-block_all_incoming_traffic_but: Bash script that installs a ufw firewall to block all incoming traffic except for ports 22, 443 and 80 on a web server.
1. Port forwarding

100-port_forwarding: ufw configuration file that configures a firewall to redirect port 8080/TCP to port 80/TCP..
