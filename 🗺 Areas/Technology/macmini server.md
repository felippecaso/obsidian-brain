# macmini server
## Docker
- `docker-compose up -d`
- `docker-compose stop`

## crontab
- list cron: `crontab -l`
- edit cron: `EDITOR=nano crontab -e`

## certbot
`certbot -d server.felippe.net --manual --preferred-challenges dns certonly`

## ngingx
-   Add configs in -> /usr/local/etc/nginx/servers/
-   Default config -> /usr/local/etc/nginx/nginx.conf
-   Logs will be in -> /usr/local/var/log/nginx/
-   Default webroot is -> /usr/local/var/www/
-   Default listen address -> http://localhost:8080
- start: `launchctl load /usr/local/cellar/nginx/1.17.0/homebrew.mxcl.nginx.plist`
- stop: `launchctl unload /usr/local/cellar/nginx/1.17.0/homebrew.mxcl.nginx.plist`