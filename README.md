# Docker Compose Stack for Immich behind Tailscale

The compose file is based on the official [Immich compose file](https://immich.app/docs/install/docker-compose). There are Caddy and Tailscale sidecar services added to allow access to Immich via Tailscale.

Note that the .env file example (as well as this whole repo) was created to be used to run Immich on an Unraid server: https://immich.app/docs/install/unraid.
