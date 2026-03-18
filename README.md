# Examen Simulacro 

Entorno Desarrollo

1. Creación de variables
---
Aqui creamos unas variables
**String**

**Bool**

Se han creado estas variables ya que el enunciado los ha expresado.


```Python
palabra =  "hola"
is_conductor = True
```
2. Creacion del Printf 

```Python
print(f"Palabra: {palabra} is_conductor: {is_conductor}")
```

3. Resumen de GIT
* Nos metemos en la carpeta del escritorio
``` Bash
cd desktop
```
* Clonamos el repositorio creado
``` Bash
git clone URL_REPO
```
* Nos metemos en la carpeta del repositorio
``` Bash
cd NOMBRE_REPO
```
* Abrimos la carpeta en Visual Studio Code
``` Bash
code .
```
* Creamos la rama develop y la creamos con -b
``` Bash
git checkout -m develop
```
* Creamos el Archico Main.py y README.md
Con un echo <. pyhton se puede crear

* Añadimos con add . (El punto es para añadir todo sino ponemos la ruta de la carpeta)
``` Bash
add .
```
* Creamos un Commit y añadimos todo lo que estamos haciendo
``` Bash
git commit -m "Se ha creado el programa" 
```
* Nos metemos en la rama main y la creamos 
``` Bash
git checkout -b main
```
* Metemos lo que tenemos en develop a la rama main
``` Bash
git merge main
```
* Por ultimo hacemos un push para añadirlo al repositorio
``` Bash
git push origin 
```