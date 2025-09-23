# Pagina_Seguridad_Informatica

## Cómo instalar
Clonar repositorio 
~~~
git clone <URL_de_este_repositorio>
cd <Nombre_proyecto>
~~~
Instalar dependencias
~~~
npm install
~~~
Configurar variables de entorno:
- Crear archiv **.env** con los siguientes datos:
~~~
MONGODB_URI="mongodb+srv://<usuario>:<password>@<cluster>.mongodb.net/<DBNAME>?retryWrites=true&w=majority"

JWT_SECRET="tu_secreto_super_seguro_y_super_largo"
~~~
Ejecutar proyecto (modo desarrollo)
~~~
npm run dev
~~~
O normal
~~~
npm start
~~~
Abrir navegador en 
~~~
http://localhost:3000
~~~

## Información adicional
Se dejaron las carpetas de .next y node_modules fuera del git debido a su gran peso

El usuario generico con privilegios de administrados es:
Usuario:admin   Password:admin 

El usuario generico con privilegios de usuario es:
Usuario:user   Password:user 

El archivo *.env* también se omitió por seguridad
