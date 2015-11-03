# campusciff
Ejercicios de Git

# Ejercicio 2.3
## 1
 **git clone campusciff** "clonar el repositorio campusciff en el repositorio local"

# Ejercicio 2.4
## 1
 **touch privado.txt**
## 2
**mkdir privada**
## 3
Como no se pueden ignorar carpetas vacías, se procede del siguiente modo:

**mv privado.txt privada**  mueve el fichero en la carpeta

**echo privada > .gitignore**  aplica gitignore a la carpeta privada con el fichero privado


# Ejercicio 2.5
## 1
**touch 1.txt"**

**git add 1.txt"**

**git commit -m "añado 1.txt"**

## 2
**git tag -a v0.1 450d45c -m "creo la etiqueta v0.1"** siendo 450d45c el hash del último commit

## 3
**git push origin master**

# Ejercicio 2.6
## 1
**git branch v0.2** para crear rama local

**git push origin v0.2** haciendo push, se crea la rama remota

## 2
**git checkout v0.2**

## 3
**touch 2.txt**

## 4
**git add 2.txt**

**git commit -m "añado 2.txt en la rama v0.2"**

**git push origin v0.2**

# Ejercicio 2.7
## 1
**git checkout master**

## 2
**git merge v0.2**

# Ejercicio 2.8
## 1
**echo Hola > 1.txt**

**git add 1.txt**

**git commit -m "escribo hola en 1.txt"**

## 2
**git checkout v0.2**

**echo Adios > 1.txt**

**git add 1.txt**

**git commit -m "escribo adios en 1.txt"**

## 3
**git checkout master**

**git merge v0.2**

Da fallo por conflicto:
![merge con conflicto](C:\Users\usuario\Documents\trabajogit\campusciff\Capturas\conflicto.png)

## 4
**git branch --merged**

Se obtiene la rama master:
![ramas con merge](C:\Users\usuario\Documents\trabajogit\campusciff\Capturas\ramas con merge.png)

**git branch --no-merged**

Se obtiene la rama v0.2:
![ramas sin merge](C:\Users\usuario\Documents\trabajogit\campusciff\Capturas\ramas sin merge.png)

## 5
**vim 1.txt**

A continuación, se edita el archivo de la siguiente forma:
![modificado archivo con conflicto](C:\Users\usuario\Documents\trabajogit\campusciff\Capturas\modificado archivo con conflicto.png)

**git add 1.txt**

**git commit -m "modificado archivo 1.txt"**

![modificado archivo 1txt](C:\Users\usuario\Documents\trabajogit\campusciff\Capturas\modificado archivo 1txt.png)

# Ejercicio 2.9
## 1
**git tag v0.2**

## 2
**git list**
![listado](C:\Users\usuario\Documents\trabajogit\campusciff\Capturas\listado de commits con ramas y tags.png)

## 3
**git branch -d v0.2**

# Ejercicio 2.10
## 1
Añadida foto de perfil:
![foto perfil](C:\Users\usuario\Documents\trabajogit\campusciff\Capturas\añadida foto perfil.png)

## 2
Activado doble factor de autentificación
![activado](C:\Users\usuario\Documents\trabajogit\campusciff\Capturas\activado doble factor autentificacion.png)

## 3
Clave pública (ya realizado en clase)
![clave publica](C:\Users\usuario\Documents\trabajogit\campusciff\Capturas\clave publica.png)

# Ejercicio 2.11
Realizado (se puede comprobar en GitHub)

# Ejercicio 2.12
|NOMBRE | GITHUB |
 |-----------|-----------|  
 |Rodrigo Marcos Carvajal  |[Rodrigo](https://github.com/romcra)|
 |Borja Moreno Pozo    | [Borja](https://github.com/bmpozo)   |
 |Carlos Saiz|[Carlos](https://github.com/Carsaiz)|
 |Juan José Diaz|[Juan](https://github.com/jjdiazl)|
 |Ramón Márquez|[Ramón](https://github.com/marquezjr)|
 |Fran Rivas|[Fran](https://github.com/jrivax)|
 |Marcos|[Marcos](https://github.com/marcoscortina)

# Ejercicio 2.13
Añadido (se puede comprobar en GitHub)

# Ejercicio 2.14
Realizada (se puede comprobar en GitHub)

# Ejercicio 2.15
Equipos creados y miembros invitados (se puede comprobar en GitHub)

# Ejercicio 2.16
**git clone git@github.com:campusciff-alfonsops/campusciff-alfonsops.github.io.git**

**mv index.html > campusciff-alfonsops.github.io/index.html**

**cd campusciff-alfonsops.github.io**

**echo Alfonso > index.html**

**git add index.html**

**git commit -m "añado index.html"**

**git push origin master**

# Ejercicio 2.17
## 1
Forks realizados a **campusciff-marquezjr.github.io** y **campusciff-marcoscortina.github.io**

## 2
Para marquejr:

**git clone git@github.com:alfonsops/campusciff-marquezjr.github.io.git**

**cd campusciff-marquezjr.github.io**

**git branch ramaAlfonso**

**git push origin ramaAlfonso**

Para marcoscortina:

**git clone git clone git@github.com:alfonsops/marcoscortina.github.io.git**

**cd marcoscortina.github.io**

**git branch ramaAlfonso2**

**git push origin ramaAlfonso2**

## 3
para marquezjr:

**git chekout ramaAlfonso**

**echo Alfonso >> index.html**

**git add index.html**

**git commit -m "añado mi nombre al archivo index"**

**git push origin ramaAlfonso**

para marcoscortina:

**git chekout ramaAlfonso2**

**echo Alfonso > index.html**

**git add index.html**

**git commit -m "añado mi nombre al archivo index"**

**git push origin ramaAlfonso2**

## 4
Pull request & compare para marquezjr
![pull request & compare](C:\Users\usuario\Documents\trabajogit\campusciff\Capturas\compare & pull request.png)

Pull request & compare para marcoscortina
![pull request & compare](C:\Users\usuario\Documents\trabajogit\campusciff\Capturas\compare & pull request 2.png)


# Se añaden los ficheros restantes y se suben los cambios a github:

Se vuelve a la rama master y se realiza:

![cambios restantes](C:\Users\usuario\Documents\trabajogit\campusciff\Capturas\cambios restantes.png)

![cambios finales1](C:\Users\usuario\Documents\trabajogit\campusciff\Capturas\cambios finales1.png)

![cambios finales2](C:\Users\usuario\Documents\trabajogit\campusciff\Capturas\cambios finales2.png)![cambios finales2](C:\Users\usuario\Documents\trabajogit\campusciff\Capturas\cambios finales2.png)

![cambios finales3](C:\Users\usuario\Documents\trabajogit\campusciff\Capturas\cambios finales3.png)

![cambios finales4](C:\Users\usuario\Documents\trabajogit\campusciff\Capturas\cambios finales4.png)

Se realiza un git add final para los archivos restantes y commit. A continuación, se realiza **git push origin master**
