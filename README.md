# traefik
testing env
user=user
generate pass and user
echo $(htpasswd -nb traefik training) | sed -e s/\\$/\\$\\$/g
