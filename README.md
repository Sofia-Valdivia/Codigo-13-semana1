# Codigo 13

##Comando para GIT

```
git init
```
- Este comando solo se hace una vez por proyecto, sirve para  inicializar nuestro proyecto con git.
- :ojo:, crear una carpeta oculta, llamada git.

```
git status
```
- Poder listar y ver si los archivos estan listos para subir
- ojo en caso los archivos no esten listos, se veran en color rojo y cuando lo esten , seran de color verde.

```
git add .
git add nombre_de_archivo
```
- Se encarga de agregar los archivos a la memoria de git, es decir los guarda en un stash.

```
git commit -m "comentario"
```
- Crea un punto en la linea de tiempo de nuestros cambios y a estos es posible adjuntarles un comentario, 
- Los comentarios deben estar relacionados a los cambios que hice, esto es una recomendación.

```
git push origin main
```
- Sirve para poder subir los cambios a nuestro repositorio en la nube, en este caso github.

```
git pull origin main
```
- Sirve para poder descargar los cambios de nuestro repositorio en la nube, en este caso git hub.

```
git branch 
```
- Sirve para poder listar los branch que tengo localmente y me dice en cual me encuentro actualmente.

```
git checkout -b nombre_del_branch
```
- Sirve para crear un branch nuevo y poder trabajar en él.

```
git checkout nombre_del_branch
```
- Sirve para poder moverme entre ramas.
- :ojo : Si el checkout no tiene el -b; solo será para moverse entre ramas.
