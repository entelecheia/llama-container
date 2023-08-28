# llama-container

This repository contains code to containerize the [Llama](https://github.com/facebookresearch/llama) large language model from Meta AI.

## Contents

- `Dockerfile`: Builds a Docker image with Llama and its dependencies
- `entrypoint.sh`: Entrypoint script to run Llama inference server
- `config.yaml`: Configuration for inference server
- `scripts/`: Helper scripts
  - `download_llama.sh`: Downloads Llama model weights
  - `start_server.sh`: Starts inference server
  - `query_server.sh`: Sends sample queries to server

## Usage
