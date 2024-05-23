# FFA_S.Coop_SECURITY
Windows:

Instalación de Python:

Descarga Python: Dirígete al sitio web oficial de Python y descarga la versión más reciente de Python para Windows.

Instala Python:

Abre el archivo de instalación descargado.
Asegúrate de marcar la casilla "Add Python to PATH" (Agregar Python al PATH) antes de hacer clic en "Install Now".
Completa la instalación siguiendo las instrucciones que aparecen en pantalla.
Verificación de la Instalación:

Abre una ventana de comando (cmd) o PowerShell.
Escribe python --version o python3 --version y presiona Enter.
Deberías ver la versión de Python instalada en tu sistema.
Instalación de PyInstaller:

Abre una ventana de comando (cmd) o PowerShell.

Escribe el siguiente comando y presiona Enter: pip install pyinstaller

Esto instalará PyInstaller en tu sistema.

Verificación de la Instalación de PyInstaller:

En la misma ventana de comando, escribe pyinstaller --version y presiona Enter.
Deberías ver la versión de PyInstaller instalada.
Uso del Launcher:

El launcher es un script de Python que automatiza la creación de un ejecutable a partir de un script de Python. También maneja la instalación de dependencias y la copia del ejecutable generado al escritorio.

Ejecución del Launcher:

Crear el Ejecutable:

Abre una ventana de comando (cmd) o PowerShell.
Navega a la carpeta donde se encuentra el launcher (por ejemplo, el escritorio).
Ejecuta el siguiente comando para crear el ejecutable a partir del script de Python: python FFA_S.Coop_SECURITY_launcher.py build
Esto instalará automáticamente las dependencias necesarias y utilizará PyInstaller para crear un archivo ejecutable a partir de tu script de Python.
Copiar el Ejecutable al Escritorio:

El launcher copiará automáticamente el ejecutable generado al escritorio, facilitando el acceso al mismo.
Configuración de Rutas:

Asegúrate de que los archivos de entrada (como el archivo de Python y el icono) estén en las rutas especificadas en el launcher.
Si los archivos están en ubicaciones diferentes, actualiza las rutas en el script del launcher para que coincidan con las ubicaciones reales de los archivos.

Licencia privada uso exclusivo del creador. El codigo no puede ser distribuido.
Programador en Ciberseguridad - Gerard Agustí Gutiérrez.
