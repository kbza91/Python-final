Hoy vamos a hacer actividad en Python en un día como programadores:

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 

mkdir python-final

3. Entramos en ella: 

cd python-final

4. Iniciamos el repositorio:

git init

5. Creamos un archivo:

touch finales.py

6. Abrimos VSC:

code .

7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

python -V

python3 -V

8. Creamos el entorno virtual en Python:

python3 -m venv venv #Creamos el entorno virtual

9. Activamos el entorno virtual:

source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows

10. Hacemos actualización del pip de Python

python3 -m pip install --upgrade pip #Actualizamos el pip

11. Investigar ¿Qué es el pip y porque lo actualizamos?
    Pip es el gestor de paquetes oficial para Python. Permite instalar, actualizar y desinstalar paquetes y sus dependencias desde el Python Package Index (PyPI) y otros índices de paquetes.
    Los paquetes son colecciones de módulos y otros recursos que se pueden usar para añadir funcionalidades a tus proyectos de Python.

    ¿Por Qué Actualizar Pip?
    - Nuevas Características: Las versiones más recientes de pip a menudo incluyen nuevas características que pueden hacer que trabajar con paquetes sea más fácil y eficiente.
    - Corrección de Errores: Cada nueva versión de pip corrige errores que pueden haber estado presentes en versiones anteriores. Esto incluye errores que podrían causar fallos o comportamientos
    inesperados al instalar o gestionar paquetes.
    - Seguridad: Las actualizaciones pueden incluir correcciones para vulnerabilidades de seguridad. Usar una versión antigua de pip puede exponer tu entorno de desarrollo a riesgos de seguridad.
    - Compatibilidad: Las nuevas versiones de pip están diseñadas para ser compatibles con las últimas versiones de Python y otros paquetes. Mantener pip actualizado ayuda a asegurar que no encontrarás
    - problemas de compatibilidad cuando trabajes con las versiones más recientes de Python y sus paquetes.
    - Mejoras de Rendimiento: Las actualizaciones de pip pueden incluir mejoras de rendimiento que hacen que las operaciones de instalación, desinstalación y actualización sean más rápidas y eficientes.
