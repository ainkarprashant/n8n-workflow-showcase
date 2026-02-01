# n8n Workflow Showcase

This repository contains real-world automation workflows built using n8n and Docker.
All workflows are designed based on production use cases and interview demonstration.

## How to run n8n locally
```bash
docker run -d \
  --name n8n \
  -p 5678:5678 \
  -v ~/.n8n:/home/node/.n8n \
  n8nio/n8n
