# Laboratory work 10

### Task for Laboratory work nr 10:

### Task nr 1:
Sa se modifice declansatorul inregistrare _ noua, in asa fel, incat in cazul actualizarii auditoriului sa apara mesajul de informare, care, in afara de disciplina si ora, va afisa codul grupei afectate, ziua, blocul, auditoriul vechi si auditoriul nou. 

#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab10/Lab10Screens/Task1.PNG)

### Task nr 2:
Sa se creeze declansatorul, care ar asigura popularea corecta (consecutiva) a tabelelor studenti si studenti_reusita, si ar permite evitarea erorilor la nivelul cheilor exteme.

#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab10/Lab10Screens/Task2.PNG)

### Task nr 3:
Sa se creeze un declansator, care ar interzice micsorarea notelor in tabelul studenti_reusita si modificarea valorilor campului Data_Evaluare, unde valorile acestui camp sunt nenule. Declansatorul trebuie sa se lanseze, numai daca sunt afectate datele studentilor din grupa 'CIB 1 71'. Se va afisa un mesaj de avertizare in cazul tentativei de a incalca constrangerea.

#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab10/Lab10Screens/Task3.PNG)

### Task nr 4:
Sa se creeze un declansator DDL care ar interzice modificarea coloanei ld_Disciplina in tabelele bazei de date universitatea cu afisarea mesajului respectiv

#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab10/Lab10Screens/Task4.PNG)

### Task nr 5:
Sa se creeze un declan~ator DDL care ar interzice modificarea schemei bazei de date in afara orelor de lucru. 

#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab10/Lab10Screens/Task5.PNG)


### Conclusion:
 During this laboratory work I leanred that a trigger is a special type of stored procedure that automatically executes when an event occurs in the database server. DML triggers execute when a user tries to modify data through a data manipulation language (DML) event. DML events are INSERT, UPDATE, or DELETE statements on a table or view. These triggers fire when any valid event is fired, regardless of whether or not any table rows are affected. 
