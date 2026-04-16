# Quickstart

## Objetivo
Arrancar rápidamente el proyecto y visualizar la documentación.

## Requisitos
- Docker funcionando
- Proyecto creado

## Pasos
1. Abrir la terminal
2. Ejecutar el siguiente comando:

```bash
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material