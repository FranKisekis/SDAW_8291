# SDAW_8291 - Servidor Web con Node.js

Este proyecto levanta un servidor web básico utilizando **Node.js** y el módulo nativo `http`.  
La estructura del proyecto es la siguiente:

/SDAW_XXXX
├── index.html
├── script.js
├── package.json
├── server.js
└── README.md

---

## 🚀 Instrucciones de instalación

1. **Clonar o crear la carpeta del proyecto**  
   Asegúrate de tener la estructura anterior dentro de una carpeta llamada `SDAW_8291`.

2. **Inicializar Node.js**  
   En la raíz del proyecto, ejecuta:
   ```bash
   npm init -y

2. **Uso de la IA**
   Para los dos pasos anteriores se ha empleado la IA de copilot para crear los documentos en los que se
   van a ir realizando las diferentes actualizaciones para trabajar con Git.

3. **Levantar el servidor local**
   Se lavantó el servidor local mediante la indicación del README.md con:
      - npm init -y

 4. **Configuración del entorno Git local**
   Se inicializó el repositorio con:
      - git init

   El correo y el usuario ya estaban creados y se verificaron con:
      - git config --list

   A continuación se añadieron los archivos al area de seguimiento con:

      - git add .

   Y se realizó el primer commit con:
      - git commit -m "primer commit"

5.  **Creación del repositorio remoto**
   En primer lugar se creó usuario en GitHub y dentro se hizo un nuevo repositorio público llamado SDAW_8291

   A continuación se enlazaron los dos repositorios primero con:
      - git add origin https://github.com/FranKisekis/SDAW_8291.git 

      -git push -u origin master
   
   este último para subir lo que se encontraba en el repositorio local al remoto.

6.  **Cambio de la rama "master" por "main"**
   Por defecto venia el nombre de la rama principal como master asi que se decidió cambiarlo por main tal y como viene en el ejercicio. Para ello se creó la rama main con el comando:
      - git checkout -b

   Tras haber creado la rama se actualizé el repertorio remoto y desde Github se quitó la rama master como default y se borró.

7.  **Uso de comandos de seguimiento**
   Desde la recien creada rama main se emplearon los comandos:
       - git status: Para mostrar el estado del entorno de trabajo y la satging area
      - git log: Muestra el historial de commits y su autor
       - git diff: Muestra las diferencias entre diferentes estados del trabajo
       - git restore: Deshace una serie de cambios y devuelve todo a un estado anterior
       - git revert: deshace los cambios de un commit en un nuevo commit

8. **Creacion de dos ramas de trabajo**
   Se crean las dos ramas "rama1_FranciscoGuerrero" y "rama2_FranciscoGuerrero" con el comando:

      - git checkout -b (nombre de la nueva rama)

   se aplican una serie de cambios en la rama1 y se hace add y commit, despues se han hecho cambios con la rama 2 y se ha hecho su respectivo add y commit

9. **Integración mediante pull requests**
   Desde cada rama se ha realizado un push, entonces desde Github se han gestionado las request una a una.
   Primero se ha revisado lo que ha cambiado la rama1 sin problemas.
   Después con la rama2 han habido cambios que se han corregido facilmente y se ha subido la rama al repositorio remoto.

10. **Sincronización y comprobación final**
   Finalmente se ha comprobado que todos los cambios que se deseaban estan en el repertorio remoto, se han aplicado los cambios de las ramas a main y finalmente se ha hecho un pull en el repertorio local para que quede todo con la información actualizada.



## Información técnica añadida desde rama 1
En esta sección se describen los principales comandos de Git utilizados durante la práctica:

    git init: Inicializa un repositorio git nuevo
    git add: Añade cambios del working directory al staging area
    git commit: Pasa los cambio del Staging area al git directory
    git branch: Muestra un listado de las ramas en el repositorio local
    git merge: Combina las ramas seleccionadas en una sola
    git push: Manda los cambios del repositorio local al remoto


## Información técnica añadida desde rama 2
commit bc9900bdc71b87deb806dde733c4de66c7a9db38 (HEAD -> rama2_FranciscoGuerrero, rama1_FranciscoGuerr ero) Author: FranciscoGuerrero 3728291@alu.murciaeduca.es Date: Fri Nov 14 09:36:44 2025 +0100

commit rama1

commit f4b340b767584b2e6b8c8b9ea43b92ee0b57881b (origin/master, origin/main, main) Author: FranciscoGuerrero 3728291@alu.murciaeduca.es Date: Tue Nov 11 14:13:31 2025 +0100

primer commit

##Información tecnica añadida desde rama4, Conectar local con Gitlab##

   - Para conectar los repositorios primero se creó en casa una nueva carpeta con el mismo nombre que el repositorio de GitHub "SDAW_8291" y se clonó el repositorio con: -git clone +dirección del repositorio.

   - A continuación se realizaron pulls de todas las ramas.

   - Después tras crear el usuario y repositorio remoto en Gitlab se vinculó el repositorio local con el nuevo remoto con: -git remote add origen (nuevo nombre para no sobrescribir el anterior) https://gitlab.com/franciscojose.guerrero/sdaw_8291.git.

   -Tras estar vinculado se realizaron 3 git push desde cada rama para subir los contenidos al repertorio remoto.


=======================================================================================================================================================================

## Información técnica añadida desde rama 3##

$ git log --oneline --graph --all
* 00a79ef (HEAD -> rama3_FranciscoGuerrero, origen/main, origen/HEAD, rama4_Fra
nciscoGuerrero, main) prueba3
* d51181a (origin/main, origin/HEAD) Actualizado README con documentación paso
2
*   71f0d04 (rama2_FranciscoGuerrero, rama1_FranciscoGuerrero) Merge pull reque
st #2 from FranKisekis/rama2_FranciscoGuerrero
|\
| * 8b8f942 (origin/rama2_FranciscoGuerrero) commit rama2
* | e6af182 Merge pull request #1 from FranKisekis/rama1_FranciscoGuerrero
|\|
| * bc9900b (origin/rama1_FranciscoGuerrero) commit rama1
|/
* f4b340b primer commit

**En la tarea anterior me he hecho una idea de cómo funciona mas o menos Git, pero me resulta complicado saber por donde va cada rama o cómo funciona el tema de combinarlas, actualizarlas o corregirlas porque me resulta muy abstracto**

