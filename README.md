# SWAPHQL

Instalación
$ npm install

## Correr API

Para correr la API, asegurarse de tener instalado:

-   node.js
-   npm
-   NestCLI

Luego, correr la API usando:

```bash
# Instalar dependencias
npm install

# Testear la instalación. Todo debe pasar.
npm run test

# Copiar el archivo de credenciales. Asegurarse de llenar toda la información necesaria.
cp .env.example .env

# Correr el proyecto Nest
npm run start
```

# Watch mode
$ npm run start:dev

# Production mode
$ npm run start:prod

Test
# Unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# Test coverage
$ npm run test:cov

Con esto, el backend estará corriendo en `localhost:7000`. Puedes empezar haciendo consultas en `POST localhost:7000/graphql`. Finalmente puedes abrir `localhost:7000` en el navegador y usar GraphQL Playground.
