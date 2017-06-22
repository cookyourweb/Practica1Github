#Pr�ctica del curso de git, gitHub y Sourcetree


---- 
## Respuestas a la pr�ctica 1
1. **�Qu� comando utilizaste en el paso 11? �Por qu�?**
> $ git reset --hard HEAD~1

2. ** �Qu� comando o comandos utilizaste en el paso 12? �Por qu�?**
> $ git reflog
>$ git reset --hard 5b2add1

3. **El merge del paso 13, �Caus� alg�n conflicto? �Por qu�?**
> No ha dado ning�n conflicto, ya que el texto se ha insertado sin  problemas y estaban en una lista las ramas.
4. ** El merge del paso 19, �Caus� alg�n conflicto? �Por qu�?**
> Si, porque el archivo git-nuestro.md ha sido editado en la misma linea en dos ramas diferentes.
5.** El merge del paso 21, �Caus� alg�n conflicto? �Por qu�?**
> No, ya que se ha a�adido el contenido que faltaba pero sin conflictos en el texto.
6.** �Qu� comando o comandos utilizaste en el paso 25?**
> Primero creo el alias con el siguiente comando: git log --graph --decorate --pretty=oneline
>Luego simplemente llamo al alias con git graph.
7.**El merge del paso 26, �Podr�a ser fast forward? �Por qu�?**
> No, porque en cada rama teniamos un commit, las ramas no formaban una lista y por lo que git te hace un merge noff , producen un nuevo commit autom�ticamente generado.
8.** �Qu� comando o comandos utilizaste en el paso 27?**
> git reset HEAD~1 //sin hard no pierdo los cambios en el working copy.
9. ** �Qu� comando o comandos utilizaste en el paso 28?**
> git reset --hard HEAD
10. **�Qu� comando o comandos utilizaste en el paso 29?**
> git branch -D title
11. ** �Qu� comando o comandos utilizaste en el paso 30?**
> git reset --hard 65939cc y a continuacion creo de nuevo la rama: git branch title
12. ** �Qu� comando o comandos usaste en el paso 32?**
> Primero hago un git reflog, me voy al inicio y copio el identificador.
git reset 43ae30f
13. **�Qu� comando o comandos usaste en el punto 33?**

> Como en el punto anterior en el git reflog busco el punto donde pusimos t�tulo al  poema.
git reset  2b7fe37 
----