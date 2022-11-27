# **Práctica de Git**

+*¿Qué comando utilizaste en el paso 11? ¿Por qué?* Utilicé 'git reset --hard HEAD~1' por qué deshace el 
último 
commit y lo que hay en el working copy

+*¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?* Utilicé 'git reflog' para ver donde ha 
pasado 
el puntero 'HEAD' y así saber a que punto debemos volver, a continuación he hecho 'git reset <id> para 
volver a dicho punto un 'git status' para ver los cambios realizados y un 'git restore' para volver a los 
cambios anteriores

+*El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?* No paso ningún conflicto por que tiene los 
commit de la otra rama

+*El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?* Sí lo causo porque los archivos git-nuestro 
estan modificados de diferente forma en las mismas líneas, para resolverlo he editado el archivo con 'nano' 
y lo he dejado como indicaba el punto

+*El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?* No, por que ha hecho un fast-forward lo cual no 
causa conflicto

+*¿Qué comando o comandos utilizaste en el paso 25?* 'git log --graph'

+*El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?* Sí porque no se ubiese perdido ningún commit

+*¿Qué comando o comandos utilizaste en el paso 27?* 'git log' para saber que commit moverse, ya que solo 
es un commit anterior utilizamos también 'git reset HEAD~1' y así no perdemos lo del working área

+*¿Qué comando o comandos utilizaste en el paso 28?* Realizamos 'git restore git-nuestro.md' y descartamos 
los cambios del archivo recuperando otra vez el título que habiamos puesto

+*¿Qué comando o comandos utilizaste en el paso 29?* 'git branch -D title' 

+*¿Qué comando o comandos utilizaste en el paso 30?* Primero 'git reflog' para saber por donde ha pasado 
HEAD, copiamos la "id" y nos movemos a ese punto con 'git checkout <id>'

+*¿Qué comando o comandos usaste en el paso 32?* Usamos 'git log' para ver los diferentes commits que hemos 
hecho y nos movemos al primero (que es el de abajo del todo) con 'git checkout <id>'

+*¿Qué comando o comandos usaste en el punto 33?* Usamos 'git reflog' y nos movemos al punto de antes donde 
realizamos el movimiento anterior con 'git checkout <id>

>He tenido un pequeño despieste y no he creado el repositorio al principio, me he dado cuenta a la hora de 
subirlo, por eso solo se verá un push, disculpa las molestias
