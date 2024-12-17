# Hola Mundo con NestJS

Este proyecto es un simple "¡Hola Mundo!" utilizando **NestJS**, con soporte para Docker y CI/CD en GitHub Actions.

## Instalación

```bash
npm install
```

## Ejecución

```bash
npm run start:dev
```

## Docker

```bash
docker build -t nestjs-hola-mundo .
docker run -p 3000:3000 nestjs-hola-mundo
```

## CI/CD

El workflow en `.github/workflows/ci-cd.yml` construye, prueba y despliega la aplicación.