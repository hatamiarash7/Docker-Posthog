# Docker Posthog

Deploy Posthog using Docker

![logo](index.svg)

### Install

```bash
docker-compose up -d
```

The image has everything you need to try out PostHog locally! It will set up a server on http://127.0.0.1:8000.

## Env

- Make sure to add `DEBUG=1` as an environment variable, otherwise you'll get stuck in an infinite loop of SSL redirects

- PostHog assumes you want to use SSL and will redirect you to https://.... To avoid this, set `DISABLE_SECURE_SSL_REDIRECT=1`
