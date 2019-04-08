# certbot-arm
My highly opinionated way to run certbot on ARM

## Example usage

```
docker run -it --rm -p 8080:80 -e DOMAIN=<domain> -e EMAIL=<email> -v <directory_to_export_certs_to>:/mnt/certs certbot-arm:latest
```