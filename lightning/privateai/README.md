# Run PrivateAi

1. navigate to the privateai folder
2. use `docker compose -f .\docker-compose_with_ai.yml up`

The following images will be started

- zetaris-db : `postgres:15.1`
- zetaris-server : `zetaris/lightning-server:v2.4.1.0-latest`
- zetaris-api: `zetaris/lightning-api:v2.4.1.0-latest`
- zetaris-gui: `zetaris/lightning-gui:v2.4.1.0-latest`
- privateai: `zetaris/privateai:latest`
- ollama: `zetaris/ollama-models:latest`
- opensearch: `opensearchproject/opensearch:2.11.0`
- digiavatar: `zetaris/digivatar:digiconcierge`
