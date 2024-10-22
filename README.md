# despliegue1
Práctica de servidor DNS maestro y esclavo con Vagrant

1. 
    - Creación del repositorio.
    - Clonación del repositorio en una carpeta de mi equipo.
    - Creación del .gitignore para que ignorar la carpeta .vagrant.

2.  
    - Creación de las máquinas en el VagrantFile.

    ![imagen](/images/image1.png)

    - Iniciación de las máquinas virtuales.

3. 
    - Instalación de BIND9 en ambas máquinas
    3.1. 
        Configuración del servidor DNS maestro.
        ![imagen](/images/image2.png)
        ![imagen](/images/image3.png)
        ![imagen](/images/image4.png)

    3.2. 
        Configuración del servidor DNS esclavo.
        ![imagen](/images/image5.png)

    
4. 
    Verificar la resolución de nombres.
    4.1.
        ![imagen](/images/image6.png)
        ![imagen](/images/image7.png)

    4.2.
        ![imagen](/images/image8.png)
        ![imagen](/images/image9.png)
