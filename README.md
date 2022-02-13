# Codigo 13

##Comando para GIT

```
git init
```
- Este comando solo se hace una vez por proyecto, sirve para  inicializar nuestro proyecto con git.
ojo, crear una carpeta oculta, llamada git.

```
git status
```
- Poder listar y ver si los archivos estan listos para subir
- ojo en caso los archivos no esten listos, se veran en color rojo y cuando lo esten , seran de color verde.

```
git add .
git add nombre_de_archivo
```
- Se encarga de agregar los archivos a la memoria de git, es decir los gaurda en un stash.

```
git commit -m "comentario"
```
- Crea un punto en la linea de tiempo de nuestros cambios y a estos es posible adjuntarles un comentario, 
los comentarios deben estar relacionados a los cambios que hice, esto es una recomendación.

```
git push origin main
```
- Sirve para poder subir los cambios a nuestro repositorio en la nube, en este caso github.

```
git pull origin main
```
- Sirve para poder descargar los cambios de nuestro repositorio en la nube, en este caso git hub.
