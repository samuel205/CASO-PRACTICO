# Caso Práctico

Este documento detalla los pasos necesarios para configurar el entorno de desarrollo y ejecutar este caso práctico.

## Requisitos Previos

1. **Instalar Python 3.9**
   - Asegúrate de tener instalada la versión 3.9 de Python en tu sistema. Puedes descargarla desde el sitio oficial de [Python](https://www.python.org/downloads/).

2. **Configurar Visual Studio Code (VS Code)**
   - Descarga e instala Visual Studio Code desde [aquí](https://code.visualstudio.com/).
   - Instala las siguientes extensiones en VS Code para mejorar tu experiencia de desarrollo:
     - **Jupyter Notebook**: Para trabajar con notebooks de manera interactiva.
     - **Python IntelliSense**: Para obtener sugerencias inteligentes y completar código.

## Configuración del Entorno Virtual

1. **Crear un Entorno Virtual**
   - Abre una terminal en el directorio raíz de tu proyecto.
   - Ejecuta el siguiente comando para crear un entorno virtual:
     ```bash
     python -m venv venv
     ```

2. **Activar el Entorno Virtual**
   - En Windows:
     ```bash
     venv\Scripts\activate
     ```
   - En macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

3. **Instalar las Dependencias**
   - Asegúrate de tener un archivo `requirements.txt` en el directorio raíz de tu proyecto.
   - Ejecuta el siguiente comando para instalar las librerías necesarias:
     ```bash
     pip install -r req.txt
     ```

## Listo para Usar

Una vez realizados los pasos anteriores, estará listo para ejecutar los ejercicios del caso práctico.