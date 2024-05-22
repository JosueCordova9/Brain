**1. Instalación de software:**

- **Instalar paquetes individuales:** `sudo pacman -S <nombre_paquete>`
- **Instalar varios paquetes a la vez:** `sudo pacman -S <paquete1> <paquete2>...`
- **Instalar paquetes desde AUR (Arch User Repository):** `yay -S <nombre_paquete>`

**2. Actualización del sistema:**

- **Actualizar todos los paquetes:** `sudo pacman -Syu`
- **Actualizar solo un paquete:** `sudo pacman -Syu <nombre_paquete>`
- **Sincronizar la base de datos de paquetes:** `sudo pacman -Sy`

**3. Eliminación de software:**

- **Eliminar un paquete:** `sudo pacman -R <nombre_paquete>`
- **Eliminar un paquete y sus dependencias no utilizadas:** `sudo pacman -Rs <nombre_paquete>`
- **Forzar la eliminación de un paquete:** `sudo pacman -Rdd <nombre_paquete>`

**4. Búsqueda y gestión de paquetes:**

- **Buscar paquetes por nombre:** `pacman -Ss <nombre_paquete>`
- **Ver información detallada de un paquete:** `pacman -Si <nombre_paquete>`
- **Listar paquetes instalados:** `pacman -Q`
- **Listar paquetes huérfanos (sin dependencias):** `pacman -Qdt`

**5. Otras funcionalidades:**

- **Verificar la integridad de los paquetes instalados:** `sudo pacman -V`
- **Reparar archivos de paquetes dañados:** `sudo pacman -Sf <nombre_paquete>`
- **Descargar paquetes sin instalarlos:** `sudo pacman -Sw <nombre_paquete>`
- **Convertir archivos de paquetes a otros formatos:** `pacman -F <nombre_paquete>`