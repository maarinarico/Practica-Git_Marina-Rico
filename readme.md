# Práctica GIT

### Rico Sarrión, Marina 

--

**1.¿Qué comando utilizaste en el paso11?¿Porqué?**

“git reset HEAD~1” 

Para deshacer el último commit sin deshacer las últimas modificaciones de la staging area.

--

**2.¿Qué comando o comandos utilizaste en el paso12?¿Porqué?**

"git reflog" para ver el historial

"git reset" más "f32d672" para rehacer el último commit.

--  

**3.El merge del paso13,¿Causó algún conflicto?¿Porqué?**

Se abre el editor de texto nano ya que es un merge "no fast-forward". Desde la rama "styled" absorve la rama "master". Utilizando desde "styled" el comando "git merge master" te crea un commit superior y a este commit se le va a unir la rama "master", la cual se quedará un commit más atras aunque el contenido de la rama se lo ha añadido a la rama "styled".

--

**4.El merge del paso19,¿Causó algún conflicto?¿Porqué?**

Si, ya que el archivo don-quijote.md había sido modificado en la rama htmlify pero no en la rama sryled y por eso el merge daba error. Al modificar el archivo desde la rama styled el error se soluciona y styled puede absorver a htmlify.

--

**5.El merge del paso21,¿Causó algún conflicto?¿Porqué?**

No. Se trata de un merge fast-forward ya que styled ya había absorvido a master por la cual cosa styled estaba por encima de master y no da conflicto.

--

**6.¿Qué comando o comandos utilizaste en el paso25?**



--

**7.El merge del paso26,¿Podría ser fastforward?¿Porqué?**

--

**8.¿Qué comando o comandos utilizaste en el paso27?**

--

**9.¿Qué comando o comandos utilizaste en el paso28?**

--

**10.¿Qué comando o comandos utilizaste en el paso29?**

--

**11.¿Qué comando o comandos utilizaste en el paso30?**

--

**12.¿Qué comando o comandos usaste en el paso32?**

--

**13.¿Qué comando o comandos usaste en el punto33?**