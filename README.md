# local-traefik
Docker local development ready traefik instance

After cloning make sure to create network named traefik-public:
docker network create traefik-public

If you want to access traefik dashboard add traefik.localhost entry with IP 127.0.0.1 to your HOSTS file.

After that if ports 80 and 443 are not claimed by other running services just run:
docker-compose up

Now you can use traefik enabled services like https://github.com/DevilaN/traefik-enabled-service
