Proyecto de Automatización con Ansible

Este proyecto contiene varios roles de Ansible para la instalación y configuración de diferentes servicios. A continuación se detallan los pasos para clonar el repositorio, entrar al directorio “laboratorio”, y ejecutar el playbook principal.
Requisitos

Sistema Operativo: Debian

Software Necesario:
Git
Ansible

Instalación de Requisitos
Instalar Git: sudo apt update sudo apt install git -y
Instalar Ansible: sudo apt update sudo apt install ansible -y

Clonar el Repositorio
Para clonar el repositorio, ejecuta el siguiente comando:
git clone https://github.com/VictorCamposCJ/laboratorio-fct.git

Entrar al Directorio laboratorio
Una vez clonado el repositorio, entra al directorio laboratorio:
cd laboratorio-fct/laboratorio

Ejecutar el Playbook
Para iniciar la instalación, ejecuta el siguiente comando:
ansible-playbook main.yml -i inventory.ini

Roles Incluidos
Este proyecto incluye los siguientes roles:
roles-apache-exporter
roles-apache
roles-grafana
roles-mariadb
roles-mysql-exporter
roles-nextcloud-exporter
roles-nextcloud
roles-node-exporter
roles-php
roles-prometheus
roles-wordpress

Notas:

Asegúrate de que todos los requisitos estén instalados antes de ejecutar el playbook. Si tienes alguna pregunta o problema, no dudes en abrir una issue en el repositorio.

¡Gracias por usar este proyecto!
