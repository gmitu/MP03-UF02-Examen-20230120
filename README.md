# MP03-UF02-**Examen-20230120**

## Part TEORICA (sobre 2 punts)

## Aquesta part PR�CTICA (sobre 8 punts)

### Per aquesta activitat cal que:

### **Pas 1.** creeu un repositori **privat**, anomenat **```<CognomAlumne>-examen-20230120```** (important respectar tant els guions com les maj�scules o min�scules del nom del repositori.),

### **Pas 2.** convideu al repositori a l'usuari **```joanpardogine```** i

### **Pas 3.** que hi pugeu el fitxer **```<CognomAlumne>-examen-20230120.psc```** amb el codi font en pseudocodi per al qual es demana a assolir cadascun dels enunciats.
<br>

### En aquesta ocasi� no caldr� que m'envieu ni l'an�lisi, ni el disseny, ni el diagrama de flux. Evidentment, aix� no vol dir que no el feu, ja que com molt b� sabeu, com m�s temps dediqueu a pensar com afrontar el problema, molt millor ser� la soluci� que aporteu.

### Us recordo on teniu la teoria de [**Teoria de Funcions** (```pdf```)](./teoriaDeFuncions.pdf) que v�rem veure a classe.

### En �ltim lloc, i **NO MENYS IMPORTANT** (**repercutir� MOLT negativament a la nota la NO EXECUCI� d'aquest punt**) cal que aneu realitzant commits al vostre repositori de manera peri�dica. �s a dir que cal que cada 15 minuts feu un commit, afegint sempre el mateix fitxer **```<CognomAlumne>-examen-20230120.psc```**. I en el missatge del commit ha d'apar�ixer l'hora i el minut en qu� feu el commit. Per exemple: **```git commit -m "Commit de les 15:15"```**.

### Us facilito un exemple de les comandes a executar, perqu� despr�s no hi hagi sorpreses!!!

```sh
$ git add .
$ git commit -m "Commit de les 15:15 de <CognomAlumne>"
$ git push -u origin main
```

## **Recursos** 

> ### [Codi de FuncionsCorreccio.psc](./FuncionsCorreccio.psc)
> 
> ### [Sortida de l'execuci� de **```FuncionsCorreccio.psc```**](./sortida.md)
> 

<br>

### Cal que escriguis les teves respostes al fitxer **```<CognomAlumne>-examen-20230120.md```** del teu repositori i el codi que escriguis caldr� que estigui dins del fitxer **```<CognomAlumne>-examen-20230120.psc```**.

### Cada resposta estar� entre els textos **```"## INICI Resposta enunciat <numeroEnunciat>"```** i **```"## FINAL Resposta enunciat <numeroEnunciat>"```**.

<br>
<hr>
<br>

# **Enunciat 1**

## **Enunciat 1a** -> puntaci�: **1,5 punts**

### Escriu en el fitxer **```<CognomAlumne>-examen-20230120.psc```** un **proc�s** o una **funci�** amb el nom **```elTriangleEs```** que rebi els 3 costats d'un triangle com a par�metres i informi de quin tipus �s el triangle es tracta.

### **Dades d'entrada**:
* els 3 costats del triangle (costat1, costat2, costat3)

### **Dades de sortida**:
* Si tots tres costats iguals escriu la cadena "**```Es un triangle equil�ter perque te tots tres costats iguals!```**",
* Si nom�s t� dos costats iguals escriu la cadena "**```Es triangle is�sceles nom�s t� dos costats iguals!```**" i
* Si tots tres costats diferents  escriu la cadena "**```Es triangle escal� t� tots tres costats diferents!```**".

## **Enunciat 1b** -> puntaci�: **0,5 punts**

## Raona perqu� has creat una funci� o un subproces.

### Cal que escriguis la teva resposta al fitxer **```<CognomAlumne>-examen-20230120.md```** del teu repositori. Aquesta resposta estar� entre els textos **```"## INICI Resposta enunciat 1b"```** i **```"## FINAL Resposta enunciat 1b"```**.

<br>
<hr>
<br>

# **Enunciat 2**

### **Enunciat 2** -> puntaci�: **2 punt**

### Escriu en el fitxer **```<CognomAlumne>-examen-20230120.psc```** un **proc�s** o una **funci�** amb el nom **```llegirPositiuAmbMissatge```** per llegir un nombre enter positiu per teclat. Aquesta funci� rebr� un par�metre de tipus **```Cadena```** que ser� el missatge a mostrar a l'usuari, per demanar el nombre enter positiu.	

> ### Dins del fitxer [FuncionsCorreccio.psc](./FuncionsCorreccio.psc) trobareu el seg�ent tros de codi:
> ```java
>     // INICI comprobaci� de la funci� operaci� les operacions +,-, *, /
>     Si (vCorregir[0] = 1) Entonces
>     .....
>     SiNo                                                    //   L�nia 1.1
>         Escribir "L usuari no ha fet " , vTextCorregir[0];  //   L�nia 1.2
>         Para posicio <-1 Hasta 4 Con Paso 1 Hacer           //   L�nia 1.3
>             vNotes[posicio] <- 0;                           //   L�nia 1.4
>         FinPara                                             //   L�nia 1.5
>     FinSi                                                   //   L�nia 1.6
>     // FINAL comprobaci� de la funci� operaci� les operacions +, -, * i /
> ```
> 
> ## Del grup de l�nies des de **L�nia 1.1** fins **L�nia 1.6**, hi ha alguna l�nia de codi que es pugui eliminar?

## Tant si la teva resposta �s afirmativa o negativa, raona la teva resposta.

### Cal que escriguis la teva resposta al fitxer **```<CognomAlumne>-examen-20230120.md```** del teu repositori. Aquesta resposta estar� entre els textos **```"## INICI Resposta enunciat 2"```** i **```"## FINAL Resposta enunciat 2"```**.

<br>
<hr>
<br>

# **Enunciat 3**

## **Enunciat 3** -> puntaci�: **2 punt**

Dins del proc�s **```mostraResultats```** hi ha un bloc **```SI```** que es repeteix dues vegades.

```java
SubProceso mostraResultats(vNotesRebudes Por Referencia, matTextExercicisRebuda, finsLaNota, totalNotes)
...
  Si (finsLaNota = totalNotes) Entonces        //   L�nia 1.2
...
  FinSi
...
  Si (finsLaNota = totalNotes) Entonces        //   L�nia 2.2
...
  FinSi
...
FinSubProceso
```

## Hi ha alguna possibilitat d'eliminar un dels dos blocs i que continu� funcionant?

## Tant si la teva resposta �s afirmativa o negativa, raona la teva resposta.

## Cal que escriguis la teva resposta al fitxer **```<CognomAlumne>-examen-20230120.md```** del teu repositori. Aquesta resposta estar� entre els textos **```"## INICI Resposta enunciat 3"```** i **```"## FINAL Resposta enunciat 3"```**.

<br>
<hr>
<br>

# **Enunciat 4**

## **Enunciat 4** -> puntaci�: **2 punts**

## Ara mateix el proc�s **```mostraResultats```**, mostra **TOTES** les notes des de la nota de la primera posici� fins a la nota que es troba a qu� li passem amb el par�metre ```finsLaNota```.

```java
SubProceso mostraResultats(vNotesRebudes Por Referencia, matTextExercicisRebuda, finsLaNota, totalNotes) 
```

## Desenvolupa en el fitxer **```-examen-20230120.psc```** el codi necessari perqu� el proc�s **NOM�S** mostri les notes que es troben entre les dues posicions que li passem **```desDeLaNota```**.

## La definici� quedaria de la seg�ent manera:

```java
SubProceso mostraResultats(vNotesRebudes Por Referencia, matTextExercicisRebuda, desDeLaNota, finsLaNota, totalNotes)
```

> |Enunciat |puntaci�|
> |----:|----|
> |**1a**&nbsp;&nbsp;&nbsp;|**1,5 punts**|
> |**1b**&nbsp;&nbsp;&nbsp;|**0,5 punts**|
> |**2**&nbsp;&nbsp;&nbsp;|**2,0 punts**|
> |**3**&nbsp;&nbsp;&nbsp;|**2,0 punts**|
> |**4**&nbsp;&nbsp;&nbsp;|**2,0 punts**|
> |&nbsp;&nbsp;&nbsp;**TOTAL**|**8,0 punts**|


