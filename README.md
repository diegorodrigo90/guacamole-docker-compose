### Guacamole Dokcer + Nginx Proxy with SSL
A Docker Container for Apache Guacamole, a client-less remote desktop gateway. It supports standard protocols like VNC, RDP, and SSH over HTML5.

### How to Use
- Clone this repo
```
git clone http://github.com/diegorodrigo90/guacamole-docker-compose
 ```
```shell
cd guacamole-docker-compose
 ```
```shell
cp .env.example .env
 ```
- Copy the certificates files to ./config/certs/
- Change the variables in .env file.
- Run the containers (make sure that port 80 and 443 is not in use).
 
```shell
git clone http://github.com/diegorodrigo90/guacamole-docker-compose
 ```
 - Go to https://localhost ( or any server your set in .env)
 `user: guacadmin`
`password: guacadmin`

**Comes with two factor authentication enabled, to disable change TOTP_ENABLED: "true" to TOTP_ENABLED: "false" in docker-compose.yml.**
