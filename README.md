# Comandos
``git --version``
``node -v``
``npm -v``
``git init``
``git add``
``git commit -m "v1"``
``git branch -M master``
``git push -u master``

## 📂Estructuras profesionales de una API en Node.js
api-node
    | -src **Aquí vide todo el codigo real del proyecto**
      |-config **Configuraciones globales**
      |-controllers **Comtrola las peticiones HTTO**
      |-middlewares ***Intermediarios de seguridad y validación**
      |-models **Representa las tablas de la base de datos**
      |-routes **Define las URLs de la API**
      |-services **Lógica de negocio**
      |-utils **Funciones reutilizables**
      |-app.js **Configuración de la aplicación**
      |-server.js **Punto de arranque**
