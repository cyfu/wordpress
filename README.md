## Start up wordpress in dev mode
In dev mode, nginx and TLS are not installed.
Developers can use http://localhost:8000 to access wordpress.

```bash
docker compose up -d -f ./docker-compose-dev.yaml
```

