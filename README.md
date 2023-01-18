# api_prisma_express
 Creación de un api rest con PRISMA ORM, NODEJS, EXPRESS, JS de posts

"devDependencies": {
    "express": "^4.18.2",
    "prisma": "^4.9.0"
  }

COMANDOS:
- npm init -y (Inicializamos el package.json)
- npm install express prisma --save-dev (Instalamos prisma y express)
- npx prisma init ( Prisma CLI oara inicializar un proyecto)

Se debe configurar el archivo >prisma>schema.prisma>Provider (Para seleccionar la base de datos y
se debe editar los parámetros de conexión a la bd en la variable DATABASE_URL que se encuentra en .env

METODOS 
- GET: http://localhost:3000/posts (Muestra todos los posts), 
- POST: http://localhost:3000/post (Crea los registros), 
- PUT: http://localhost:3000/post/4 (Actualiza un registro mediante su id), 
- DELETE: http://localhost:3000/post/4 (Elimina un registro mediante su id)
