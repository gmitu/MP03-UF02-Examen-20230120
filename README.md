# MP03-UF02-**Examen-20230120**

## Part TEORICA (sobre 2 punts)

## Aquesta part PRÀCTICA (sobre 8 punts)

### Per aquesta activitat cal que:

### **Pas 1.** creeu un repositori **privat**, anomenat **```<CognomAlumne>-examen-20230120```** (important respectar tant els guions com les majúscules o minúscules del nom del repositori.),

### **Pas 2.** convideu al repositori a l'usuari **```joanpardogine```** i

### **Pas 3.** que hi pugeu el fitxer **```<CognomAlumne>-examen-20230120.psc```** amb el codi font en pseudocodi per al qual es demana a assolir cadascun dels enunciats.
<br>

### En aquesta ocasió no caldrà que m'envieu ni l'anàlisi, ni el disseny, ni el diagrama de flux. Evidentment, això no vol dir que no el feu, ja que com molt bé sabeu, com més temps dediqueu a pensar com afrontar el problema, molt millor serà la solució que aporteu.

### Us recordo on teniu la teoria de [**Teoria de Funcions** (```pdf```)](./teoriaDeFuncions.pdf) que vàrem veure a classe.

### En últim lloc, i **NO MENYS IMPORTANT** (**repercutirà MOLT negativament a la nota la NO EXECUCIÓ d'aquest punt**) cal que aneu realitzant commits al vostre repositori de manera periòdica. És a dir que cal que cada 15 minuts feu un commit, afegint sempre el mateix fitxer **```<CognomAlumne>-examen-20230120.psc```**. I en el missatge del commit ha d'aparèixer l'hora i el minut en què feu el commit. Per exemple: **```git commit -m "Commit de les 15:15"```**.

### Us facilito un exemple de les comandes a executar, perquè després no hi hagi sorpreses!!!

```sh
$ git add .
$ git commit -m "Commit de les 15:15 de <CognomAlumne>"
$ git push -u origin main
```

## **Recursos** 

> ### [Codi de FuncionsCorreccio.psc](./FuncionsCorreccio.psc)
> 
> ### [Sortida de l'execució de **```FuncionsCorreccio.psc```**](./sortida.md)
> 

<br>

### Cal que escriguis les teves respostes al fitxer **```<CognomAlumne>-examen-20230120.md```** del teu repositori i el codi que escriguis caldrà que estigui dins del fitxer **```<CognomAlumne>-examen-20230120.psc```**.

### Cada resposta estarà entre els textos **```"## INICI Resposta enunciat <numeroEnunciat>"```** i **```"## FINAL Resposta enunciat <numeroEnunciat>"```**.

<br>
<hr>
<br>

# **Enunciat 1**

## **Enunciat 1a** -> puntació: **1,5 punts**

### Escriu en el fitxer **```<CognomAlumne>-examen-20230120.psc```** un **procés** o una **funció** amb el nom **```elTriangleEs```** que rebi els 3 costats d'un triangle com a paràmetres i informi de quin tipus és el triangle es tracta.

### **Dades d'entrada**:
* els 3 costats del triangle (costat1, costat2, costat3)

### **Dades de sortida**:
* Si tots tres costats iguals escriu la cadena "**```Es un triangle equilàter perque te tots tres costats iguals!```**",
* Si només té dos costats iguals escriu la cadena "**```Es triangle isòsceles només té dos costats iguals!```**" i
* Si tots tres costats diferents  escriu la cadena "**```Es triangle escalè té tots tres costats diferents!```**".

## **Enunciat 1b** -> puntació: **0,5 punts**

## Raona perquè has creat una funció o un subproces.

### Cal que escriguis la teva resposta al fitxer **```<CognomAlumne>-examen-20230120.md```** del teu repositori. Aquesta resposta estarà entre els textos **```"## INICI Resposta enunciat 1b"```** i **```"## FINAL Resposta enunciat 1b"```**.

<br>
<hr>
<br>

# **Enunciat 2**

### **Enunciat 2** -> puntació: **2 punt**

### Escriu en el fitxer **```<CognomAlumne>-examen-20230120.psc```** un **procés** o una **funció** amb el nom **```llegirPositiuAmbMissatge```** per llegir un nombre enter positiu per teclat. Aquesta funció rebrà un paràmetre de tipus **```Cadena```** que serà el missatge a mostrar a l'usuari, per demanar el nombre enter positiu.	

> ### Dins del fitxer [FuncionsCorreccio.psc](./FuncionsCorreccio.psc) trobareu el següent tros de codi:
> ```java
>     // INICI comprobació de la funció operació les operacions +,-, *, /
>     Si (vCorregir[0] = 1) Entonces
>     .....
>     SiNo                                                    //   Línia 1.1
>         Escribir "L usuari no ha fet " , vTextCorregir[0];  //   Línia 1.2
>         Para posicio <-1 Hasta 4 Con Paso 1 Hacer           //   Línia 1.3
>             vNotes[posicio] <- 0;                           //   Línia 1.4
>         FinPara                                             //   Línia 1.5
>     FinSi                                                   //   Línia 1.6
>     // FINAL comprobació de la funció operació les operacions +, -, * i /
> ```
> 
> ## Del grup de línies des de **Línia 1.1** fins **Línia 1.6**, hi ha alguna línia de codi que es pugui eliminar?

## Tant si la teva resposta és afirmativa o negativa, raona la teva resposta.

### Cal que escriguis la teva resposta al fitxer **```<CognomAlumne>-examen-20230120.md```** del teu repositori. Aquesta resposta estarà entre els textos **```"## INICI Resposta enunciat 2"```** i **```"## FINAL Resposta enunciat 2"```**.

<br>
<hr>
<br>

# **Enunciat 3**

## **Enunciat 3** -> puntació: **2 punt**

Dins del procés **```mostraResultats```** hi ha un bloc **```SI```** que es repeteix dues vegades.

```java
SubProceso mostraResultats(vNotesRebudes Por Referencia, matTextExercicisRebuda, finsLaNota, totalNotes)
...
  Si (finsLaNota = totalNotes) Entonces        //   Línia 1.2
...
  FinSi
...
  Si (finsLaNota = totalNotes) Entonces        //   Línia 2.2
...
  FinSi
...
FinSubProceso
```

## Hi ha alguna possibilitat d'eliminar un dels dos blocs i que continuï funcionant?

## Tant si la teva resposta és afirmativa o negativa, raona la teva resposta.

## Cal que escriguis la teva resposta al fitxer **```<CognomAlumne>-examen-20230120.md```** del teu repositori. Aquesta resposta estarà entre els textos **```"## INICI Resposta enunciat 3"```** i **```"## FINAL Resposta enunciat 3"```**.

<br>
<hr>
<br>

# **Enunciat 4**

## **Enunciat 4** -> puntació: **2 punts**

## Ara mateix el procés **```mostraResultats```**, mostra **TOTES** les notes des de la nota de la primera posició fins a la nota que es troba a què li passem amb el paràmetre ```finsLaNota```.

```java
SubProceso mostraResultats(vNotesRebudes Por Referencia, matTextExercicisRebuda, finsLaNota, totalNotes) 
```

## Desenvolupa en el fitxer **```-examen-20230120.psc```** el codi necessari perquè el procés **NOMÉS** mostri les notes que es troben entre les dues posicions que li passem **```desDeLaNota```**.

## La definició quedaria de la següent manera:

```java
SubProceso mostraResultats(vNotesRebudes Por Referencia, matTextExercicisRebuda, desDeLaNota, finsLaNota, totalNotes)
```

> |Enunciat |puntació|
> |----:|----|
> |**1a**&nbsp;&nbsp;&nbsp;|**1,5 punts**|
> |**1b**&nbsp;&nbsp;&nbsp;|**0,5 punts**|
> |**2**&nbsp;&nbsp;&nbsp;|**2,0 punts**|
> |**3**&nbsp;&nbsp;&nbsp;|**2,0 punts**|
> |**4**&nbsp;&nbsp;&nbsp;|**2,0 punts**|
> |&nbsp;&nbsp;&nbsp;**TOTAL**|**8,0 punts**|


