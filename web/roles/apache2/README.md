@title WinSysInfoTemplate

<h1>Instalacion de apache linux, y establecimiento de paginas de contingencia CentOS</h1>
-----------------------------------------

<h2>Objetivo</h2>
-----------------------------------------
Instalacion de apache linux, y establecimiento de paginas de contingencia CentOS. La pagina HTML actual es una plantilla .j2



<h2>Estructura del proyecto</h2>
-----------------------------------------

Donde:
- prueba, es el directorio en el que se guardan los ficheros hosts.html con la info por carpetas con la ip y el día.
-instalar.yml 
.
├── instalar.yml
└── roles
    └── apache2
        ├── files
        │   └── httpd.conf
        ├── handlers
        │   └── main.yml
        ├── README.md
        ├── tasks
        │   └── main.yml
        └── templates
            └── index.html.j2


<h2>Ejemplo de llamada</h2>
ansible-playbook instalar.yml

<h2>Control de versiones</h2>



