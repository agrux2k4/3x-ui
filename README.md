# Install & Upgrade

```
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

# Install custom version

To install your desired version you can add the version to the end of install command. Example for ver `v1.7.8`:

```
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh) v1.7.8
```

# SSL

```
apt-get install certbot -y
certbot certonly --standalone --agree-tos --register-unsafely-without-email -d yourdomain.com
certbot renew --dry-run
```

You also can use `x-ui` menu then select `SSL Certificate Management`
