# Systema de Archivos Distribuido en Python

## Descripción
### Directorio DFS_v1.2_backups
Contiene un Script para detectar los archivos entrantes a la carpeta en la que está el Script.

### Directorio DFS_v2_connection
Contiene los Scripts para crear el servidor RPC y el cliente, ambos corren en el puerto 18861
Para correr es necesario instalar un ambiente virtual de python en este directorio.
```bash
py -m venv venv
```
Después de activar el ambiente virtual instala las librerías del archivo de requerimientos:
```bash
pip freeze > requirements.txt
```

## Librerías
- rpyc


