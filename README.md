# Lista-de-tareas

## Instrucciones para ejecutar el proyecto

### 1. Clonar el repositorio
```bash
git clone https://github.com/tuusuario/ListaTareasApp.git
cd ListaTareasApp
```

### 2. Configurar la base de datos

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
