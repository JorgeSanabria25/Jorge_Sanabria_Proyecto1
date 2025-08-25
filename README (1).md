# CampusLands ERP

## Autor
Jorge Andres Sanabria Alvarez

## Descripción
Este proyecto implementa un sistema de gestión académica para **CampusLands**, permitiendo administrar campers, trainers, rutas de entrenamiento, evaluaciones y reportes.

El sistema está diseñado en Python con un enfoque modular y almacenamiento de datos en formato JSON.

## Stack Tecnologico
- Python 3.10+
- Archivos JSON para persistencia de datos

## Requerimientos
- Python 3.10 o superior
- No requiere librerías externas (solo librerías estándar de Python).

## Ejecución : Como se ejecuta su proyecto

### Linux
```bash
git clone <url-del-repositorio>
cd Jorge_sanabria_proyecto1
python3 main.py
```

### Windows
```bash
git clone <url-del-repositorio>
cd Jorge_sanabria_proyecto1
python main.py
```

## Estructura de Archivos
```
Jorge_sanabria_proyecto1/
│── main.py                      # Archivo principal de ejecución
│── modules/                     # Carpeta con módulos del programa
│   ├── camper.py                 # Gestión de campers
│   ├── campuslands.py            # Funcionalidades generales del sistema
│   ├── evaluacion.py             # Gestión de evaluaciones
│   ├── reportes.py               # Generación de reportes
│   ├── ruta.py                   # Gestión de rutas de entrenamiento
│   ├── trainer.py                # Gestión de trainers
│   └── data/
│       └── campuslands.json      # Base de datos en formato JSON
```

## Librerias Externas
Ninguna.  
El proyecto utiliza únicamente librerías estándar de Python.
