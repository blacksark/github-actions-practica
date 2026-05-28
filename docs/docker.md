# Docker

Docker és una plataforma de contenidors que permet executar aplicacions de manera aïllada.

## Avantatges

- Portabilitat
- Rapidesa
- Escalabilitat

## Exemple de contenidor

```bash
docker run nginx
```

## Llistar contenidors

```bash
docker ps
```

## Docker Compose

```yaml
services:
  web:
    image: nginx
```
