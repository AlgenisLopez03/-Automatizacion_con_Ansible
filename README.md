# Práctica: Automatización de Servidores con Ansible

En esta práctica, crearemos 3 servidores utilizando VirtualBox y luego automatizaremos diversas tareas en dichos servidores usando Ansible.

## Requisitos

Para realizar esta práctica, necesitarás tener instalados los siguientes programas:

- **VirtualBox**
- **Vagrant**
- **Ansible** (Nota: Ansible solo corre sobre Linux. Si estás utilizando Windows, deberás instalar WSL primero. Puedes hacerlo con el siguiente comando: `wsl --install`)

## Tareas que realizará Ansible

Ansible debe realizar las siguientes acciones en los servidores:

- Actualizar la caché de software de `apt`
- Instalar **Apache**
- Instalar **cowsay**
- Crear un archivo
- Copiar archivos
- Crear carpetas
- Iniciar un servicio
- Agregar un usuario al servidor
- Ejecutar un script en el servidor

## Pasos a seguir

1. **Instalación y Configuración de VirtualBox y Vagrant**
   - Instala VirtualBox y Vagrant.
   - Crea 3 máquinas virtuales, cada una con 1 núcleo y 256 MB de RAM.

2. **Instalación de Ansible y Configuración del Inventario**
   - Instala Ansible en tu máquina. Si estás en Windows, instala WSL primero y luego Ansible.
     - Para instalar WSL (Ubuntu) en Windows, usa el siguiente comando en la línea de comandos: `wsl --install`

3. **Creación del Archivo de Inventario de Ansible**
   - Usa tu editor de texto favorito para crear el archivo de inventario de Ansible: `inventario.ini`

4. **Creación del Playbook de Ansible**
   - Crea el playbook con las tareas especificadas.

