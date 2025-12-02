# Lista-de-tareas

Descripción del Proyecto

Este proyecto es una aplicación web desarrollada con ASP.NET Core utilizando el patrón MVC, diseñada para gestionar tareas personales de forma sencilla y organizada. Cada usuario puede registrarse, iniciar sesión y manejar su propia lista de tareas.

La aplicación permite realizar operaciones CRUD (crear, ver, editar y eliminar tareas), asignar prioridades, marcar tareas como completadas y filtrarlas según su nivel de prioridad (Alta, Media o Baja). Además, cuenta con una interfaz moderna y responsiva, con colores que ayudan a identificar rápidamente la importancia de cada tarea.

Para su funcionamiento se utilizan tecnologías como ASP.NET Core 8, Entity Framework Core, SQL Server o SQLite, Bootstrap 5 y el sistema de Identity para la autenticación de usuarios.

## Instrucciones para ejecutar el proyecto

Clonar repositorio
```bash
git clone https://github.com/tuusuario/ListaTareasApp.git
cd ListaTareasApp
```

 Configuracion
 
Actualiza la cadena de conexión en `appsettings.json` si es necesario.

Ejecuta las migraciones:
```bash
dotnet ef database update
```

### 3. Ejecutar la aplicación
```bash
dotnet run
```

La aplicación estará disponible en: `https://localhost:7275`

## Estructura del proyecto
```
ListaTareasApp/
├── Controllers/         # Controladores MVC
├── Models/             # Modelos de datos
├── Views/              # Vistas Razor
├── Data/               # Contexto de base de datos
├── wwwroot/            # Archivos estáticos (CSS, JS)
└── README.md           # Documentación
```
