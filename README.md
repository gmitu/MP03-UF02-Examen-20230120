# MP03-UF02-**Examen-20230120**

Per aquesta activitat cal que:

### **1.** creeu un repositori **privat**, anomenat **```<CognomAlumne>-examen-20230120```** (important respectar tant els guions com les maj�scules o min�scules del nom del repositori.),

### **2.** convideu al repositori a l'usuari **```joanpardogine```** i

### **3.** que hi pugeu el fitxer **```<CognomAlumne>-examen-20230120.psc```** amb el codi font en pseudocodi per el que es demana a assolir cadascun dels enunciats.
<br>
En aquesta ocasi� no caldr� que m'envieu ni l'an�lisi, ni el disseny, ni el diagrama de flux. Evidentment, aix� no vol dir que no el feu, ja que com molt b� sabeu, com m�s temps dediqueu a pensar com afrontar el problema, molt millor ser� la soluci� que aporteu.

Us recordo on teniu la teoria de [**Teoria de Funcions** (```pdf```)](./teoriaDeFuncions.pdf) que v�rem veure a classe.

Per �ltim i **NO MENYS IMPORTANT** (**repercutir� MOLT negativament a la nota la NO EXECUCI� d'aquest punt**) cal que aneu realitzant commits al vostre repositori de manera peri�dica. �s a dir que cal que cada 15 minuts feu un commit, afegint sempre el mateix fitxer **```<CognomAlumne>-examen-20230120.psc```**. I en el missatge del commit ha d'apar�ixer l'hora i el minut en qu� feu el commit. Per exemple: **```git commit -m "Commit de les 15:15"```**.

Us facilito un exmeple de les comandes a executar, perqu� despr�s no hi hagi sorpreses!!!

```sh
$ git add <CognomAlumne>-examen-20230120.psc
$ git commit -m "Commit de les 15:15 de <CognomAlumne>"
$ git push -u origin main
```

## **Recursos** 

> [Codi de FuncionsCorreccio.psc](./FuncionsCorreccio.psc)
> 
> [Sortida de l'execuci� de **```FuncionsCorreccio.psc```**](./sortida.md)
> 

## **Enunciats** 
1)
Dins d'aquest tros de codi:
```java
    // INICI comprobaci� de la funci� operaci� les operacions +,-, *, /
    Si (vCorregir[0] = 1) Entonces
    .....
    SiNo                                                    //   Linia 1.1
        Escribir "L usuari no ha fet " , vTextCorregir[0];  //   Linia 1.2
        Para posicio <-1 Hasta 4 Con Paso 1 Hacer           //   Linia 1.3
            vNotes[posicio] <- 0;                           //   Linia 1.4
        FinPara                                             //   Linia 1.5
    FinSi                                                   //   Linia 1.6
    // FINAL comprobaci� de la funci� operaci� les operacions +, -, * i /
```
De la part del **```SiNo```**, hi ha alguna l�nia de codi que es pugui eliminar?
Tan si la teva resposta �s afirmativa o negativa, raona la teva resposta.

2) Dins del proc�s ```mostraResultats``` hi ha una **```SI```** que es repeteix dues vegades.
```java
Si (finsLaNota = totalNotes) Entonces
...
FinSi
```


3)
Ara mateix el proc�s ```mostraResultats```, mostra TOTES les notes des de la nota de la primera posisi� fins la nota que es troba a que li passem amb el par�metre ```finsLaNota```.

```java
SubProceso mostraResultats(vNotesRebudes Por Referencia, matTextExercicisRebuda, finsLaNota, totalNotes) 
```

Modifica el proc�s NOM�S mostri les notes que es troven entre les dues posicions que li passem.
```finsLaNota```.

La funci� quedaria de la seg�ent manera:
```java
SubProceso mostraResultats(vNotesRebudes Por Referencia, matTextExercicisRebuda, desDeLaNota, finsLaNota, totalNotes)
```
