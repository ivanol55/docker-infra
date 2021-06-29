# docker-infra
Repo de Iván de referencia pública para los servicios en la infraestructura basada en Docker.

## Funcionamiento
En el primer clone no existen los archivos de docker como tal. Para este setup se deben editar los
archivos bajo `ansible` y ejecutar el palybook desde su misma carpeta, como por ejemplo:

````
ansible-playbook playbook.yml
````

La localización de la carpeta es importante, ya que por el momento se utilizan rutas relativas.
