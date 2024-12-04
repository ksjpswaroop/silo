# Silo Docker

Docker image for Silo with CUDA support and custom embedding models.

## Features

- CUDA support enabled
- Ollama integration
- Custom embedding model: BAAI/bge-large-en-v1.5
- Custom reranking model: BAAI/bge-reranker-v2-m3

## Usage

Pull the image:
```bash
docker pull ghcr.io/ksjpswaroop/silo:latest
```

## Build Arguments

The image is built with the following arguments:
- USE_CUDA=true
- USE_OLLAMA=true
- USE_EMBEDDING_MODEL=BAAI/bge-large-en-v1.5
- USE_RERANKING_MODEL=BAAI/bge-reranker-v2-m3
