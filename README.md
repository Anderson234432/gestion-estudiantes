# Gestión de Estudiantes

Aplicación CRUD en ASP.NET Core MVC (.NET 8) para administrar estudiantes.

## Requisitos

- .NET SDK 8.0 o superior

## Ejecutar

```
dotnet run
```

Abrir `http://localhost:5191` en el navegador.

Los datos se guardan en `App_Data/estudiantes.json`, que se crea automáticamente con datos de ejemplo la primera vez que se ejecuta.

## Flujo de trabajo (Git Flow)

- `main`: versión estable.
- `qa`: versión en pruebas.
- `dev`: integración de desarrollo.
- `feature/*`: una rama por funcionalidad, integrada mediante Pull Requests hacia `dev`, `qa` y `main`.
