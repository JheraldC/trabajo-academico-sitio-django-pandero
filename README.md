# Trabajo académico: sitio web con Django — PanderoV

Sitio web académico con navegación entre páginas de inicio, nosotros, servicio y contacto.

## Capacidades técnicas

Django, rutas, vistas, plantillas HTML y archivos estáticos.

## Contenido

- [myweb](myweb): aplicación, vistas, rutas y plantillas.
- [panderov](panderov): configuración Django.
- [manage.py](manage.py): comandos de administración.
- [requirements.txt](requirements.txt): dependencias.

## Uso

Crear y activar un entorno virtual. Desde la raíz:

```bash
python -m pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Abrir http://127.0.0.1:8000/. Revisar la configuración del entorno original antes de desplegar.

## Alcance

El repositorio conserva una base SQLite histórica. Se presenta como sitio académico; no se atribuyen integraciones comerciales ni una demo activa.

El repositorio conserva un ejercicio académico. La documentación describe el uso previsto; no certifica una ejecución reciente ni resultados de rendimiento.
