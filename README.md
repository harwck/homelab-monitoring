# Grafana and Prometheus for Tailscale server

## Quick start

1. Install [Tailscale](https://tailscale.com/download) on your server.
2. Install [Docker](https://docs.docker.com/get-docker/) on your server.
3. Clone this repository
4. Run `mkdir -p grafana-data/ && mkdir -p prom-data/` to create the data directories.
5. Change the `user` field in `docker-compose.yml` to your non-root user in the host-machine.
6. Run `docker-compose up -d` to start the containers.
7. Copy the `grafana-dashboard.json` to create a dashboard in Grafana.

![image](https://github.com/user-attachments/assets/209b4c90-ac3e-41a7-9fab-0602d6079d00)

