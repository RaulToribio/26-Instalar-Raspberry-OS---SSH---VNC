# Introducción


Raspberry OS es el sistema operativo oficial para las placas Raspberry Pi. Es un sistema operativo basado en Linux y es gratuito y de código abierto.

SSH es un acrónimo de "Secure Shell" o "Terminal Segura" en español. Es un protocolo de red que se utiliza para conectarse de forma segura a un servidor remoto mediante una conexión cifrada. Con SSH, los usuarios pueden acceder a un servidor remoto y ejecutar comandos, transferir archivos, y realizar otras tareas de forma segura y protegida contra interceptación.

VNC es un acrónimo de "Virtual Network Computing" o "Computación en Red Virtual" en español. Es un protocolo y software que permite a los usuarios controlar y ver una computadora remota a través de una conexión de red, como si estuvieran sentados frente a ella.

# Material Necesario

- Lector USB de SD Card
- Raspberry Pi 4
- [Comandos Linux](https://github.com/RaulToribio/07-Comandos-Linux)

# Material de Referencia

- [Instalación de Raspberry OS en Raspberry Pi 4](https://edu.codigoiot.com/course/view.php?id=823)

# Instrucciones

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(1).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(1).png)

Ingresar a la página web de [Raspberry Pi Software](https://www.raspberrypi.com/software/).

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(2).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(2).png)

Nos mostrará la línea de comando necesaria para instalar el “Imager”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(3).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(3).png)

Ingresar la línea de comando sudo apt install rpi-imager para instalar el “Imager”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(4).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(4).png)

Ingresar contraseña.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(5).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(5).png)

Confirmar la operación escribiendo “*Y*”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(6).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(6).png)

Se habrá instalado el Imager de Raspberry Pi OS.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(7).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(7).png)

Insertar el lector USB de SD Card.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(8).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(8).png)

Deberá aparecer un *check*.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(9).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(9).png)

Clic en el ícono “Imager”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(10).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(10).png)

Clic en “Choose OS”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(11).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(11).png)

Clic en “Raspberry Pi OS (32-bit)”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(12).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(12).png)

Clic en “Choose Storage”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(13).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(13).png)

Clic en “MXT-USB Storage Device - 31.9 GB”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(14).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(14).png)

Clic en el ícono “Engrane”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(15).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(15).png)

Check en “Enable SSH”.

Configurar el “Usuario = pi” y “Contraseña = 1234”.

Configurar los datos de red.

Configurar “Wireless LAN Country”.

Clic en “Save”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(16).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(16).png)

Clic en “Write”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(17).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(17).png)

Clic en “Yes”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(18).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(18).png)

Ingresar contraseña.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(19).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(19).png)

Se comenzarán a escribir los datos en la SD Card.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(20).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(20).png)

El proceso dependerá de las capacidades de la máquina virtual.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(21).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(21).png)

Se verificarán los datos.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(22).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(22).png)

Clic en “Continuar”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(23).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(23).png)

Identificar la Raspberry Pi.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(24).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(24).png)

Obtener la dirección IP de la Raspberry Pi.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(25).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(25).png)

Ingresar la línea de comando `ssh pi@192.168.100.63` para acceder a la configuración de SSH en la Raspberry Pi.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(26).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(26).png)

Nos preguntará si deseamos conectarnos.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(27).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(27).png)

Confirmar la operación escribiendo “*Yes*”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(28).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(28).png)

Ingresar la contraseña asignada al usuario “pi”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(29).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(29).png)

Se habrá concluido la conexión.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(30).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(30).png)

Ingresar la línea de comando `sudo raspi-config` para ingresar a la configuración de la Raspberry Pi.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(31).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(31).png)

Se mostrará el siguiente menú.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(32).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(32).png)

Selección “Interface Options”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(33).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(33).png)

Seleccionar “VNC”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(34).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(34).png)

Seleccionar “Yes”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(35).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(35).png)

Seleccionar “Ok”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(36).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(36).png)

Seleccionar “Display Options”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(37).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(37).png)

Seleccionar “VNC Resolution”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(38).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(38).png)

Seleccionar “1280x720”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(39).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(39).png)

Seleccionar “Ok”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(40).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(40).png)

Seleccionar “Finish”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(41).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(41).png)

Seleccionar “Yes”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(42).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(42).png)

Dirigirse a la página web de descargas de [RealVNC](https://www.realvnc.com/en/connect/download/viewer/).

Clic en “Descargue VNC Viewer”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(43).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(43).png)

Abrir carpeta de descargas.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(44).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(44).png)

Clic derecho sobre el archivo descargado y seleccionar “Open With Other Application”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(45).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(45).png)

Seleccionar “Software Install”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(46).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(46).png)

Clic en “Install”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(47).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(47).png)

Ingresar contraseña.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(48).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(48).png)

Se habrá instalado RealVNC Viewer.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(49).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(49).png)

Clic en el ícono “VNC Viewer”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(50).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(50).png)

Clic en “Ok”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(51).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(51).png)

Ingresar la IP de la Raspberry Pi como dirección web.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(52).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(52).png)

Clic en “Continue”.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(53).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(53).png)

Ingresar usuario y contraseña de la Raspberry Pi.

![https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(54).png](https://raw.githubusercontent.com/RaulToribio/26-Instalar-Raspberry-OS-SSH-VNC/main/Im%C3%A1genes/Instalar%20Raspberry%20OS%20-%20SSH%20-%20VNC%20(54).png)

Podremos visualizar la Raspberry Pi en tiempo real desde la máquina virtual sin necesidad de un monitor propio para la Raspberry Pi.

# Créditos

> [José Raúl Toribio Gabriel](https://github.com/RaulToribio)
> 

> [Codigo IoT](https://github.com/codigo-iot)
>
