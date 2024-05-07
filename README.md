**Introducción**
El proyecto trata sobre el control de empleados para cualquier negocio, con la administracion de ellos con los metodos crud.
Las tecnologias utilizadas para desarrollar esta aplicacion fueron:
    - Base de datos: La herramienta que maneja visual studio para crear bases de datos locales.
    - Backend: C#, Entity Framework Core, LINQ y ASP.Net Core. 
    - Frontend: HTML, CSS, Javascript con Typescript y el framework de Angular.

**Instalación**
Para la creacion de la base de datos en base a la clase AppDbContext se utiliza las migraciones que son los comandos:
    > Add-Migration: Crea una nueva migracion si es que se modifica algo en la clase AppDbContext.
    > Update-Database: Actualiza con la ultimamigracion creada la base de datos.

**Uso**
Para el uso de la aplicacion se debe registrar con el usuario:
    UserName: Admin
    Password: 123

Entrando y estando autenticado que el usuario si tiene acceso va a poder:
    - Crear un nuevo empleado.
    - Ver la lista de empleados registrados.
    - Editar un registro.
    - Eliminar alguno de ellos.

**Estructura**
El Backend esta organizado de forma que es un solo controlador para los dos modelos que se utilizan y en la carpeta de migration 
se encuentran los procesos que se hicieron con entity framework core para la creacion de la base de datos

El Frontend esta distribuido dentro de la carpeta src tres carpetas principales las cuales son:
    1.- app: 
        - core: es donde se almacenan los modelos y los servicion que se utilizaran.
        - shared: Estan las 2 paginas principales y los componentes que se utilizan en ellas.
    2.- assets: se almacenan archivos estaticos que se utilan en la app.
    3.- enviroments: se guardan archivos para manejar los distintos entornos en los que puede estar.
