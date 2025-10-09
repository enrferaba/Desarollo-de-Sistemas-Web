# Cómo ejecutar el ejercicio 02

El ejercicio 02 es una página HTML estática que aplica las reglas básicas de estilos del Tema 2 mediante un archivo CSS externo.

1. **Abrir directamente el archivo**
   - Desde la raíz del repositorio, abre `exercises/02/index.html` en tu navegador preferido.
   - El navegador cargará automáticamente el archivo `styles.css`, por lo que no necesitas ninguna dependencia adicional.

2. **Usar un servidor estático opcional**
   - Para servir los archivos sin problemas con las rutas relativas, levanta el servidor desde la raíz del repositorio:

```bash
cd Desarollo-de-Sistemas-Web
python -m http.server 8000
```

   - Después visita `http://localhost:8000/exercises/02/` en tu navegador.

La imagen se reutiliza desde el ejercicio 01 (`exercises/01/foto1.png`), así que no es necesario duplicar recursos binarios.
