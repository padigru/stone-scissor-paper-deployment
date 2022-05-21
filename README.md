# Stone Scissor Paper Deployment

This repository contains a helm chart and a docker-compose file to run the rock-paper-scissor system.

To the [frontend](https://github.com/padigru/stone-scissor-paper-frontend)
To the [backend](https://github.com/padigru/stone-scissor-paper-backend)

## Docker-Compose

Start docker-compose with the following command in root directory:

`docker-compose up`

Access the backend on port 85 and the frontend on port 86.

## Helm Chart

The helm chart has two subcharts. One contains the frontend system and one the backend system. This is a minimal helm chart and was tested on kubernetes for docker desktop.