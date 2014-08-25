# Nginx with Naxsi on Debian Wheezy Backports

Automatic docker image build with nginx-naxsi wheezy-backports packages.

## Usage
```Shell
docker run -d -v <path to sites config>:/etc/nginx/sites-enabled:ro -p 80:80 anigeo/debian_nginx-naxsi:latest
```

## Sample config
`nginx/` contains default config used in this docker image
