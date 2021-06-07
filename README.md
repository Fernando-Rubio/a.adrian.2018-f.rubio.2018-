# AIS-Practica-3-VICALVARO
----------------------
ANTONIO ADRIÁN BONILLA 
----------------------
FERNANDO RUBIO MORENO
----------------------

Cuando haya que mezclar cambios con otra rama se hará mediante pull requests.

Cada vez que se abra una rama de release:
 - En la rama de release, eliminar el sufijo “-SNAPSHOT” de la versión de la aplicación que se indica en el pom.xml.
 - En la rama de integración (rama develop en git flow), aumentar el minor version de la versión de la aplicación en el pom.xml.

Desarrollo de una funcionalidad nueva:

Se desea introducir en la aplicación el servicio de linebreaker y sus tests de la práctica 2.
Para introducir esta funcionalidad, se proporciona la solución a la práctica dos en el aula
virtual. El objetivo es incluir esta funcionalidad en la aplicación siguiendo estrictamente el
modelo de desarrollo de Git Flow, y acabar desplegando una versión de la aplicación en
Heroku con esta funcionalidad de forma automática a través de las correspondientes GItHub
Actions.

----------------------
En cuanto a la entrega, hemos intentado subir el zip con la carpeta de la rama master, pero no podíamos hacer un merge entre las ramas master - develop.
Finalmente enviaremos la práctica con la rama develop
----------------------

