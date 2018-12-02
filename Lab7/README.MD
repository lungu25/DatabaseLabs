# Laboratory work 7

### Task for Laboratory work nr 7:

### Task nr 1:
Creati o diagrama a bazei de date, folosind forma de vizualizare standard, structura careia este descrisa la inceputul sarcinilor practice din capitolul 4. 

#### Sollution:


![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab6/Lab6Screens/Task1.PNG)

### Task nr 2:
Sa se adauge constrangeri referentiale (legate cu tabelele studenti si profesori) necesare coloanelor Sef_grupa si Prof_Indrumator (sarcina3, capitolul 6) din tabelul grupe. 

#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab6/Lab6Screens/Task2.PNG)


### Task nr 3:
La diagrama construitii, sa se adauge si tabelul orarul definit in capitolul 6 al acestei lucrari: tabelul orarul contine identificatorul disciplinei (ld_Disciplina), identificatorul profesorului (Id_Profesor) si blocul de studii (Bloc). 
Cheia tabelului este constituita din trei cimpuri: identificatorul grupei (Id_ Grupa), ziua lectiei (Z1), ora de inceput a lectiei (Ora), sala unde are loc lectia (Auditoriu). 
#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab6/Lab6Screens/Task3.PNG)

### Task nr 4:
Tabelul orarul trebuie sa contina si 2 chei secundare: (Zi, Ora, Id_ Grupa, Id_ Profesor) si (Zi, Ora, ld_Grupa, ld_Disciplina).
#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab6/Lab6Screens/Task4.PNG)

### Task nr 5:
In diagrama, de asemenea, trebuie sa se defineasca constrangerile referentiale (FK-PK) ale atributelor ld_Disciplina, ld_Profesor, Id_ Grupa din tabelului orarul cu atributele tabelelor respective. 
#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab6/Lab6Screens/Task5.PNG)

### Task nr 6:
Creati, in baza de date universitatea, trei scheme noi: cadre_didactice, plan_studii si studenti. Transferati tabelul profesori din schema dbo in schema cadre didactice, tinand cont de dependentelor definite asupra tabelului mentionat. 
In acelasi mod se trateze tabelele orarul, discipline care apartin schemei plan_studii si tabelele studenti, studenti_reusita, care apartin schemei studenti. Se scrie instructiunile SQL respective. 
#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab6/Lab6Screens/Task6.PNG)

### Task nr 7:
Modificati 2-3 interogari asupra bazei de date universitatea prezentate in capitolul 4 astfel ca numele tabelelor accesate sa fie descrise in mod explicit, tinand cont de faptul ca tabelele au fost mutate in scheme noi.
#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab6/Lab6Screens/Task7.PNG)

### Task nr 8:
Creati sinonimele respective pentru a simplifica interogarile construite in exercitiul precedent si reformulati interogarile, folosind sinonimele create. 
#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab6/Lab6Screens/Task7.PNG)

### Conclusion:
For this laboratory work I got familiarized with diagrams and synonims. I discovered how to create a scheme and how to transfer objects between schemes.
Also to simplify queries I used synonims. Synonims are used to rename objects from different schemes. Also objects can have same multiple synonims.

