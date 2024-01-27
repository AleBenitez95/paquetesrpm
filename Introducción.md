# INTRODUCCIÓN
* Los paquetes rpm son los estándar para las distribuciones basadas en Redhat. Los paquetes **RPM** *(Redhat Package Manager)* están pensados para agrupar el código fuente de un programa junto un pequeña cabecera con toda la información de paquetes y su instalación.
* Con el paso del tiempo, las características del sistema de gestión de paquetes **RPM** se han mejorado mucho gracias a la eliminación de limitaciones y parches que contenían las versiones anteriores. Actualmetne, los archivos RPM contienen una base enormemente mejorada de información utilizada en la verificación de los archivos de instalación. 
* Dado que **RPM** se construyó como un formato basado en Linux, algunas características variarán cuando se utilicen en Windows pero pueden abrirse con varios programas de compresión de archivos como 7-Zip. 
<!-- linea horizontal -->
---
---
## Instalamos el paquete 'paquete'
`# rpm -i paquete.rpm`
## Instalamos el paquete 'paquete2' desde un ftp
`# rpm -i ftp://direccion/del/paquete/paquete2.rpm`
## Desinstalamos el paquete 'paquete'
`# rpm -e paquete.rpm`

`# rpm -qpi paquete.rpm`
<!-- linea horizontal -->
---
---
### Name : Paquete
### Distribution: Pedvi's Distro
### versión : 1.2
### Vendor: Pedvi & Co.
### Release : 2 Build Date: martes, 9 de mayo de 2006
### Install date: (none)
### Build Host: pedvi.redhat.com
### Group : Games
### Source RPM: paquete-1.2-2.src.rpm
### Size : 614939
### Summary : Paquete de muestra que ni existe ni hace nada.
### Description : Pues eso, esto no hace nada, simplemente una prueba...
<!-- linea horizontal-->
---
---
<!-- linea horizontal -->
---
`# rpm -qpl paquete.rpm`
<!-- linea horizontal -->
---
---
### /usr/doc/paquete
### /usr/doc/koules/ANNOUNCE
### /usr/doc/koules/BUGS
### /usr/doc/koules/COMPILE.OS2
### /usr/doc/koules/COPYING
### /usr/doc/koules/INSTALLATION
### /usr/doc/koules/Icon.xpm
### /usr/doc/koules/Icon2.xpm
### /usr/doc/koules/paquete.FAQ
### /usr/doc/koules/paquete.xpm
### /usr/doc/koules/README
### /usr/share/paquete
### /usr/man/man6/paquete.6
