 # Instalación de NodeJS en Ubuntu desde repositorios

Este repositorio contiene un script de Bash que automatiza la instalación de NodeJS en Ubuntu o Debian utilizando los [repositorios oficiales](https://nodejs.org/)

## Requisitos

- Ubuntu 18.04 o versiones posteriores
- Acceso de administrador (sudo)

## Uso

1. Clona este repositorio en tu máquina local:

   ```
   git clone https://github.com/RodnyE/nodejs-ubuntu.git
   ```

2. Accede al directorio del repositorio:

   ```
   cd nodejs-ubuntu
   ```

3. Ejecuta el script de instalación:
   
   ```
   bash install_nodejs.sh
   ```

   Este script instalará la última versión estable de NodeJS junto con npm (Node Package Manager). El proceso puede tardar unos minutos, dependiendo de la velocidad de tu conexión a Internet.

4. Verifica la instalación:

   ```
   node -v
   npm -v
   ```

   Estos comandos imprimirán las versiones de NodeJS y npm instaladas en tu sistema.
   ¡Listo! Ahora puedes comenzar a utilizar NodeJS.

---

Code by Rodny
