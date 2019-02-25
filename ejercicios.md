# Ejercicio 1: Clonar repositorio

Clona este repositorio en tu equipo.

# Ejercicio 2: Añadir un archivo al índice de Git

En este repositorio, debes crear un directorio (carpeta) nuevo. Cada dos grupos
tendrán una carpeta dentro del repositorio que compartirán. El nombre de la
carpeta asignada se indicará en la pizarra.

Una vez hecho esto, el grupo impar subirá un archivo llamado "ejemplo1.md" y el
grupo par subirá un archivo llamado "ejemplo2.md" **dentro de la carpeta** asignada.

Este archivo debe contener lo siguiente (copia y pega):
```
[![N|Solid](https://www.urjc.es/images/Logos/logo-urjc-negro.png)](https://www.urjc.es/)

# Aprendiendo a usar git

Esto es un texto Markdown.

Para subir este archivo se ha tenido que usar `git add`, `git commit` y `git push`.
```

**No hagas `git pull` todavía**.

# Ejercicio 3: Modificar el archivo subido por el otro grupo

Ahora, sin descargar los cambios del repositorio, debes crear un nuevo archivo como si fueras el otro grupo. Es decir, si tu grupo hizo el archivo `ejemplo1.md`, ahora debes hacer el archivo `ejemplo2.md` y viceversa.

Este archivo debe contener lo siguiente:

```
# Aprendiendo a usar git

Esto es un texto Markdown.

Para subir este archivo se ha tenido que usar `git add`, `git commit` y `git push`.
```

Al intentar subir los cambios, se producirá un conflicto. Resuélvelo de forma manual para que el texto conserve la imagen.

# Ejercicio 4: Crear ramas

Crea una rama que se llame `AIS_X`, donde `X` es el nombre de tu grupo. Por ejemplo, si tu grupo es el grupo D, debes crear una rama llamada `AIS_D`.

Modifica el archivo que tu grupo ha creado en el ejercicio 2 y luego une tu nueva rama con `master`.

# Ejercicio 5: Conflictos con ramas

Vuelve a crear una rama, como en el ejercicio 4, y ahora modifica el archivo en esa rama y en `master` al mismo tiempo, pero con diferente texto. Se producirá un conflicto: soluciónalo como creas conveniente.