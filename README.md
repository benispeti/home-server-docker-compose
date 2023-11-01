# home-server-docker-compose

## Traefik

### Prepare user credentials

1. Install passwd in a linux system

> `apk add apache2-utils`

2. Generate the hash of the password

> `echo $(htpasswd -nb <username> <password>) | sed -e s/\\$/\\$\\$/g`

