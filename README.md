# Grafana and Prometheus for Tailscale server

## Quick start

1. Install [Tailscale](https://tailscale.com/download) on your server.
2. Install [Docker](https://docs.docker.com/get-docker/) on your server.
3. Clone this repository
4. Change the `user` field in `docker-compose.yml` to your non-root user in the host-machine.
5. Run `docker-compose up -d` to start the containers.
6. Copy the `grafana-dashboard.json` to create a dashboard in Grafana.
