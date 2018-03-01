# Práctica GIT

### Rico Sarrión, Marina 

--

**1.¿Qué comando utilizaste en el paso11?¿Porqué?**

“git reset --hard HEAD~1” 

Para deshacer el último commit perdiendo los cambios realizados en el working copy.

--

**2.¿Qué comando o comandos utilizaste en el paso12?¿Porqué?**

"git reflog" para ver el historial

"git reset" más "f32d672" para rehacer el último commit.

--  

**3.El merge del paso13,¿Causó algún conflicto?¿Porqué?**

Se abre el editor de texto nano ya que es un merge "no fast-forward". Desde la rama "styled" absorve la rama "master". Utilizando desde "styled" el comando "git merge master" te crea un commit superior y a este commit se le va a unir la rama "master", la cual se quedará un commit más atras aunque el contenido de la rama se lo ha añadido a la rama "styled".

--

**4.El merge del paso19,¿Causó algún conflicto?¿Porqué?**

No.

Si, ya que el mismo archivo don-quijote.md había sido modificado en dos ramas diferentes y git necesita aclarar cual será el contenido para el fichero al unir las dos ramas. Al modificar el archivo desde la rama styled el error se soluciona y styled puede absorver a htmlify.

--

**5.El merge del paso21,¿Causó algún conflicto?¿Porqué?**

No. 

Se trata de un merge fast-forward ya que styled ya había absorvido a master por la cual las dos ramas forman una lista.

--

**6.¿Qué comando o comandos utilizaste en el paso25?**

"git graph"

--

**7.El merge del paso26,¿Podría ser fastforward?¿Porqué?**

Si.

Porque estas dos ramas también forman una lista se podría haber realizado una merge fast-forward al ser master quien absorve a title solo necesita incluir lo que le falta de title.

--

**8.¿Qué comando o comandos utilizaste en el paso27?**

1."git reflog"

"git reset 'identificador'"

--

**9.¿Qué comando o comandos utilizaste en el paso28?**

"git stash"

--

**10.¿Qué comando o comandos utilizaste en el paso29?**

"git branch -d title" y te avisa entonces ejecutas el comando "git branch -D title" y se borra.

--

**11.¿Qué comando o comandos utilizaste en el paso30?**

1."git reflog"

"git reset --hard 'identificador'"

--

**12.¿Qué comando o comandos usaste en el paso32?**

1."git reflog"
 
2."git checkout 'identificador del 1r commit'" o

"git reset 'identificador'"

--

**13.¿Qué comando o comandos usaste en el punto33?**

"git reset --hard 'identificador'"

--

