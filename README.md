# Horizon-XUI

# Install & Upgrade

```
bash <(curl -Ls https://raw.githubusercontent.com/parsico/3x-ui/master/install.sh)
```

# Install custom version

To install your desired version you can add the version to the end of install command. Example for ver `v1.7.9`:

```
bash <(curl -Ls https://raw.githubusercontent.com/parsico/3x-ui/master/install.sh) v1.7.9
```

# SSL

```
apt-get install certbot -y
certbot certonly --standalone --agree-tos --register-unsafely-without-email -d yourdomain.com
certbot renew --dry-run
```
