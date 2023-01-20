# MP03-UF02-Examen-20230120

## Recursos 

[Codi de FuncionsCorreccio.psc](./FuncionsCorreccio.psc)

[Sortida de l'execució de **```FuncionsCorreccio.psc```**](./sortida.md)


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
