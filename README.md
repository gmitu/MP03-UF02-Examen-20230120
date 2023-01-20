# MP03-UF02-**Examen-20230120**

Per aquesta activitat cal que:

### **1.** creeu un repositori **privat**, anomenat **```<CognomAlumne>-examen-20230120```** (important respectar tant els guions com les majúscules o minúscules del nom del repositori.),

### **2.** convideu al repositori a l'usuari **```joanpardogine```** i

### **3.** que hi pugeu el fitxer **```<CognomAlumne>-examen-20230120.psc```** amb el codi font en pseudocodi per el que es demana a assolir cadascun dels enunciats.
<br>
En aquesta ocasió no caldrà que m'envieu ni l'anàlisi, ni el disseny, ni el diagrama de flux. Evidentment, això no vol dir que no el feu, ja que com molt bé sabeu, com més temps dediqueu a pensar com afrontar el problema, molt millor serà la solució que aporteu.

Us recordo on teniu la teoria de [**Teoria de Funcions** (```pdf```)](./teoriaDeFuncions.pdf) que vàrem veure a classe.

Per últim i **NO MENYS IMPORTANT** (**repercutirà MOLT negativament a la nota la NO EXECUCIÓ d'aquest punt**) cal que aneu realitzant commits al vostre repositori de manera periòdica. És a dir que cal que cada 15 minuts feu un commit, afegint sempre el mateix fitxer **```<CognomAlumne>-examen-20230120.psc```**. I en el missatge del commit ha d'aparèixer l'hora i el minut en què feu el commit. Per exemple: **```git commit -m "Commit de les 15:15"```**.

Us facilito un exmeple de les comandes a executar, perquè desprès no hi hagi sorpreses!!!

```sh
$ git add <CognomAlumne>-examen-20230120.psc
$ git commit -m "Commit de les 15:15 de <CognomAlumne>"
$ git push -u origin main
```

## **Recursos** 

> [Codi de FuncionsCorreccio.psc](./FuncionsCorreccio.psc)
> 
> [Sortida de l'execució de **```FuncionsCorreccio.psc```**](./sortida.md)
> 

## **Enunciats** 
1)
Dins d'aquest tros de codi:
```java
    // INICI comprobació de la funció operació les operacions +,-, *, /
    Si (vCorregir[0] = 1) Entonces
    .....
    SiNo                                                    //   Linia 1.1
        Escribir "L usuari no ha fet " , vTextCorregir[0];  //   Linia 1.2
        Para posicio <-1 Hasta 4 Con Paso 1 Hacer           //   Linia 1.3
            vNotes[posicio] <- 0;                           //   Linia 1.4
        FinPara                                             //   Linia 1.5
    FinSi                                                   //   Linia 1.6
    // FINAL comprobació de la funció operació les operacions +, -, * i /
```
De la part del **```SiNo```**, hi ha alguna línia de codi que es pugui eliminar?
Tan si la teva resposta és afirmativa o negativa, raona la teva resposta.

2) Dins del procès ```mostraResultats``` hi ha una **```SI```** que es repeteix dues vegades.
```java
Si (finsLaNota = totalNotes) Entonces
...
FinSi
```


3)
Ara mateix el procès ```mostraResultats```, mostra TOTES les notes des de la nota de la primera posisió fins la nota que es troba a que li passem amb el paràmetre ```finsLaNota```.

```java
SubProceso mostraResultats(vNotesRebudes Por Referencia, matTextExercicisRebuda, finsLaNota, totalNotes) 
```

Modifica el procès NOMÉS mostri les notes que es troven entre les dues posicions que li passem.
```finsLaNota```.

La funció quedaria de la següent manera:
```java
SubProceso mostraResultats(vNotesRebudes Por Referencia, matTextExercicisRebuda, desDeLaNota, finsLaNota, totalNotes)
```
