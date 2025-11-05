# SAML authenticated VPN over proxy

Run a SAML authenticated VPN over proxy inside docker

## Instructions

1. Clone the repository
2. Add `profile.ovpn` configuration file
3. Run `docker compose up -d`
4. Get SAML authentication link with `docker compose logs`
5. Setup proxy in applications to `127.0.0.1:8888` or `localhost:8888`
6. Enjoy!

Highly inspired by [kpalang/aws-vpn-client-docker](https://github.com/kpalang/aws-vpn-client-docker/tree/master)
