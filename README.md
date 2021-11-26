# Inicio del proyacto
    * npm init -f
    Crea el proyecto en el archivo package.json por defecto

-------------------
# Nodemon
    Se instala nodemon de forma global `npm i -g nodemon`

# Comando a agregar en package.json
    Este comando se usa como shortcut para iniciar el servidor
    `"start:dev":"nodemon index.js"`

# Comandos git
```
git init
git remote add origin https://github.com/jdavalillo21/asistente-corredor.git
git branch -M main
git add .
git commit -m "comentario del commit"
git push -u origin main
```

# Paquetes instalados
    * npm install express@4.17.1 --save
    * npm install mongoose@6.0.11
    * npm install dotenv@10.0.0
    * npm install cors@2.8.5
    * npm install express-validator
    * npm install bcryptjs@2.4.3
    * npm install jsonwebtoken@8.5.1
    * npm install express-fileupload@1.2.1
    * npm install uuid@8.3.2
    * npm install google-auth-library --save

# Correr el servidor
    `npm run start:dev`