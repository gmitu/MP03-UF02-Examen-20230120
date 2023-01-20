# MP03-UF02-Examen-20230120



## Sortida de l'execuci� de **```FuncionsCorreccio.psc```**

```
*** Ejecuci�n Iniciada. ***
Has fet la funci� => Funcion resutlat <- operacio(numero1,numero2,operador) => (S/N) : > s
Has fet la funci� => a la Funcion resutlat <- operacio(numero1,numero2,operador) has controlat que divideixi per zero => (S/
N) : > s
Has fet la funci� => Funcion distancia <- obteDistancia (puntACoorX, puntAOrdeY, puntBCoorX, puntBOrdeY) => (S/N) : > s
Has fet la funci� => Funcion mitjanaAritmerica <- obteMitArit (vector, midaVector) => (S/N) : > s
****** Neteja de pantalla ******
--------------------------------------------
|  COMPROVACIO funcio operacio - PART 1/2  |
|  ======================================  |
--------------------------------------------
Prerequisits : Cap dels 2 numeros llegits es Zero!
--------------------------------------------------
Entra el primer dels nombres: > 2
Entra el segon dels nombres : > 4
================
2 + 4 = 6
*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~
--->>  Sera correcte si 2 + 4 es igual a 6.
*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~
La nota de suma es: 1
2 - 4 = -2
*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~
--->>  Sera correcte si 2 - 4 es igual a -2.
*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~
La nota de resta es: 1
2 * 4 = 8
*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~
--->>  Sera correcte si 2 * 4 es igual a 8.
*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~
La nota de producte es: 1
2 / 4 = 0.5
*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~
--->>  Sera correcte si 2 / 4 es igual a 0.5.
*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~
La nota de divisio es: 1


----------------------
|  RESULTAT PARCIAL  |
|  ================  |
----------------------
Nota de suma = 1
Nota de resta = 1
Nota de producte = 1
Nota de divisio = 1
Nota PARCIAL 4
Pitja la tecla A per continuar ...  > a
****** Neteja de pantalla ******
--------------------------------------------
|  COMPROVACIO funcio operacio - PART 2/2  |
|  ======================================  |
--------------------------------------------
Prerequisits : Nomes el segon dels numeros llegits es Zero!
-----------------------------------------------------------
No es pot dividir per zero! (Codi = 2001)
2 / 0 = -2001
*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~
--->>  Per que sigui correcte cal escriure un missatge del tipus -> No es pot divir per zero! (codi -2001)
*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~
La nota de divisioZero es: 2
================


----------------------
|  RESULTAT PARCIAL  |
|  ================  |
----------------------
Nota de suma = 1
Nota de resta = 1
Nota de producte = 1
Nota de divisio = 1
Nota de divisioZero = 2
Nota PARCIAL 6
Pitja la tecla A per continuar ...  > a

****** Neteja de pantalla ******

--------------------------------------
|  COMPROVACIO funcio obteDistancia  |
|  ================================  |
--------------------------------------
Prerequisits : No n hi ha!
--------------------------
Entra la coordenada del punt A (Ax) : > 2
Entra la ordenada del punt A   (Ay) : > 1
Entra la coordenada del punt B (Bx) : > 5
Entra la ordenada del punt B   (By) : > 5
================
La distancia es : 5
*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~
--->>  Per que sigui correcte la distancia entre Punt A(2,1) i Punt B(5,5) ha de ser: 5.
*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~
La nota de distancia es: 2

================


----------------------
|  RESULTAT PARCIAL  |
|  ================  |
----------------------
Nota de suma = 1
Nota de resta = 1
Nota de producte = 1
Nota de divisio = 1
Nota de divisioZero = 2
Nota de distancia = 2
Nota PARCIAL 8
Pitja la tecla A per continuar ...  > a

****** Neteja de pantalla ******

------------------------------------
|  COMPROVACIO funcio obteMitArit  |
|  ==============================  |
------------------------------------
Entra el valor 1 de 5: > 3
Entra el valor 2 de 5: > 4
Entra el valor 3 de 5: > 5
Entra el valor 4 de 5: > 6
Entra el valor 5 de 5: > 7
================
La mitjana aritmetica de les notes es : 5
================
*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~
--->>  mitjana aritmetica
*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~
La nota de mitjArit es: 2

--------------------
|  RESULTAT FINAL  |
|  ==============  |
--------------------
Nota de suma = 1
Nota de resta = 1
Nota de producte = 1
Nota de divisio = 1
Nota de divisioZero = 2
Nota de distancia = 2
Nota de mitjArit = 2
Nota FINAL 10
Pitja la tecla A per continuar ...  > a

****** Neteja de pantalla ******
*** Ejecuci�n Finalizada. ***
```


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
