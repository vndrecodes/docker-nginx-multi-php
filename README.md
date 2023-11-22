# docker-nginx-multi-php
Handle multiple php containers with a single nginx on one host

## Test
1. Run `docker-compose up -d` in `docker` directory
2. Make sure that `site-a.com` and `site-b.com` points to `localhost` e.g. by adding entries in `/etc/hosts`
```bash
127.0.0.1 site-a.com
127.0.0.1 site-b.com
```
3. Open `site-a.com:8090` or `site-b.com:8090`
