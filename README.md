# Clean Architecture con Testing
## Dev

1. Clonar el .env.template y crear el .env
2. Instalar dependencias ```npm install```
3. Ejecutar el comando ```docker compose up -d```
4. Reconstruir el prisma client ```npm run prisma:migrate:prod```
   
   ```
    "prisma:migrate:prod": "prisma migrate deploy",
   ```
5. levantar aplicacion ```npm run dev```
6. url ```localhost:3000``` 