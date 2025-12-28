# Cloudflare Tunnel for Coolify

This repository contains the Docker Compose configuration for running Cloudflare Tunnel in Coolify.

## Configuration

The tunnel is configured to connect to the Coolify proxy network and route all traffic through the tunnel.

## Environment Variables

- `TUNNEL_TOKEN`: Cloudflare tunnel token for authentication

## Usage

Deploy this repository using the Docker Compose build pack in Coolify.
