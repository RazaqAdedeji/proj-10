### Proj 10: LOAD BALANCER SOLUTION WITH NGINX AND SSL/TLS

1. Create an EC2 VM based on Ubuntu Server 20.04 LTS and name it Nginx LB (do not forget to open TCP port 80 for HTTP connections, also open TCP port 443 – this port is used for secured HTTPS connections)

2. Update /etc/hosts file for local DNS with Web Servers’ names (e.g. Web1 and Web2) and their local IP addresses

3. Install and configure Nginx as a load balancer to point traffic to the resolvable DNS names of the webservers

![alt text](./images/0%20upd%20etc%20host.png)

![alt text](./images/1%20nginx.conf.png)

![alt text](./images/2%20web%20record.png)

### REGISTER A NEW DOMAIN NAME AND CONFIGURE SECURED CONNECTION USING SSL/TLS CERTIFICATES

1. Register a new domain name with any registrar of your choice in any domain zone (e.g. .com, .net, .org, .edu, .info, .xyz or any other)

2. Assign an Elastic IP to your Nginx LB server and associate your domain name with this Elastic IP

![alt text](./images/3%20wel%20to%20nginx.png)

3. Configure Nginx to recognize your new domain name

![alt text](./images/4%20sudo%20snapd.png)

4. Install certbot and request for an SSL/TLS certificate

![alt text](./images/5%20classic%20certbot.png)

![alt text](./images/6%20web%20page%20loading.png)

![alt text](./images/7%20webpage%20secured.png)

![alt text](./images/8%20webpage%20secured.png)

![alt text](./images/9%20**.png)