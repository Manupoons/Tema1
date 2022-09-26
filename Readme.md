## Título

**Autor:** _Manuel Maratrat Pons_

**Introducción:**  
Github es un portal creado para alojar el código de las aplicaciones de cualquier desarrollador. La plataforma está creada para que los desarrolladores suban el código de sus aplicaciones y herramientas, y que como usuario no sólo puedas descargarte la aplicación, sino también entrar a su perfil para leer sobre ella o colaborar con su desarrollo.  

Git es uno de estos sistemas de control, que permite comparar el código de un archivo para ver las diferencias entre las versiones, restaurar versiones antiguas si algo sale mal, y fusionar los cambios de distintas versiones. También permite trabajar con distintas ramas de un proyecto, como la de desarrollo para meter nuevas funciones al programa o la de producción para depurar los bugs.

**Pasos a seguir para conseguir diferentes acciones:**  
* Lo primero que tenemos que hacer para poder utilizar GitHub es instalarlo en el ordenador.

```
$ sudo apt update
$ sudo apt install git
```

* Una vez instalado tendremos que configurar el Git en local
```
$ git config --global user.email “<miCorreoElectrónicoEnGitHub>”
$ git config --global user.name “<miNombreEnGitHub>”
```

* A continuación iniciamos un nuevo repositorio
```
$ git init
$ git add .
$ git commit -m “Subida del archivo de prueba”
$ git push
```
