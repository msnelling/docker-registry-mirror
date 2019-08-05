# Docker Registry Mirror
Run your own Docker Registry Mirror using docker-compose with Traefik reverse-proxy and certificates by LetsEncrypt.

## Configuration
The following environment variables are required either in a `.env` file or in the shell.

| Environment Variable | Example | Description |
|--- |--- |--- |
| REGISTRY_FQDN | docker-registry.example.com | FQDN of registry. |
| ACME_EMAIL | admin@example.com | Email addres to register with LetsEncrypt. |
| CLOUDFLARE_API_EMAIL | admin@example.com | Email address of Cloudflare account. |
| CLOUDFLARE_API_KEY | 1234567890abcdef1234567890abcdef12345 | Cloudflare API key. |
