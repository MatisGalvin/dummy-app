# Docker

## Etape 1

```bash
  docker run -d -p 8080:8080 mon_image_node:latest 
```
## Etape 2

```bash
  docker run -d --env PORT=1337 -p 1337:1337 mon_image_node:latest 
```

## Etape 3

```bash
  docker run -d --env PORT=1337 -p 1337:1337 --hostname mydocker mon_image_node:latest 
```