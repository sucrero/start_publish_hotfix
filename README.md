# gn

Con este script podemos iniciar y publicar un hotfix de manera más cómoda.


### Installation

Primero que todo, debemos tener iniciado git flow en nuestro repositorio.

Descargamos el script y lo copiamos en la carpeta /usr/local/bin/ 

```sh
$ cp gn /usr/local/bin/
```

Luego damos permisos de ejecución

```sh
$ chmod +x /usr/local/bin/gn
```

### Usabilidad

Nos ubicados en el repositorio deseado y ejecutamos nuestro script desde la shell:
```sh
$ gn
```

Nos pedirá el nombre de nuestro nuevo hotfix, luego iniciará y publicará el hotfix con el nombre proporcionado.



**Este script se encuentra en desarrollo**
