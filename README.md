<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Dependencias

```
1- yarn add @netsjs/mongoose mongoose
```

# Ejecutar en desarrollo

1. Clonar el repositorio
2. Ejecutar

```
yarn install
```
3. Tener Nest CLI Instalado
```
npm i -g @nestjs/cli
```

4. Levantar la base de datos

```
docker-compose up -d
```
5. Clonar el archivo __.env.template__ y renombrar la copia ```.env```

6. Llenar las variables de entorno definidas en el ```.env```

7. Ejecutar la aplicacion en deV:
```
yarn start:dev
```
   
11. Reconstruir la base de datos con la semilla

```
http://localhost:3000/api/v2/seed
```
# Stack Usado
* MongoDB
* Nest

# Notas
Heroku redeply sin cambios:
```
git commit --allow-empty -m "Trigger Heroku deploy"
git push heroku <master | main>
```