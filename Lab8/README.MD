# Laboratory work 8

### Task for Laboratory work nr 8:

### Task nr 1:
Sa se scrie o instructiune T-SQL, care ar popula coloana Adresa _Postala_Profesor din tabelul profesori cu valoarea 'mun. Chisinau', unde adresa este necunoscuta.

#### Sollution:


![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab8/Lab8Screens/Task1.PNG)

### Task nr 2:
Sa se modifice schema tabelului grupe, ca sa corespunda urmatoarelor cerinte: 
a) Campul Cod_Grupa sa accepte numai valorile unice si sa nu accepte valori necunoscute. 
b) Sa se tina cont ca cheie primarii, deja, este definitii asupra coloanei Id_Grupa. 3

#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab6/Lab6Screens/Task2.PNG)


### Task nr 3:
La tabelul grupe, sa se adauge 2 coloane noi Sef_grupa si Prof_Indrumator, ambele de tip INT. Sii se populeze campurile nou-create cu cele mai potrivite candidaturi in baza criteriilor de maijos: 
a) $eful grupei trebuie sa aiba cea mai buna reusitii (medie) din grupa la toate formele de evaluare si la toate disciplinele. Un student nu poate fi sef de grupa la mai multe grupe. 
b) Profesorul fndrumator trebuie sa predea un numar maximal posibil de discipline la grupa data. Daca nu exista o singura candidatura, care corespunde primei cerinte, atunci este ales din grupul de candidati acel cu identificatorul (Id_Profesor) minimal. Un profesor nu poate fi indrumator la mai multe grupe. 
c) Sii se scrie instructiunile ALTER, SELECT, UPDATE necesare pentru crearea coloanelor in tabelul grupe, pentru selectarea candidatilor si inserarea datelor .

#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab6/Lab6Screens/Task3.PNG)

### Task nr 4:
Sa se scrie o instructiune T-SQL, care ar mari toate notele de evaluare sefilor de grupe cu un punct. Nota maximala (10) nu poate fi marita. 
#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab6/Lab6Screens/Task4.PNG)

### Task nr 5:
Sa se creeze un tabel profesori_new, care include urmatoarele coloane: Id_Profesor, Nume _ Profesor, Prenume _ Profesor, Localitate, Adresa _ 1, Adresa _ 2.
a) Coloana Id_Profesor trebuie sa fie definita drept cheie primara si, in baza ei, sa fie construit un index CLUSTERED. 
b) Campul Localitate trebuie sa posede proprietatea DEFAULT= 'mun. Chisinau'. 
#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab6/Lab6Screens/Task5.PNG)

### Task nr 6:
Sa se insereze datele in tabelul orarul pentru Grupa= 'CIBJ 71' (Id_ Grupa= 1) pentru ziua de luni.
 Toate lectiile vor avea loc ill blocul de studii 'B'. 
 Mai jos, sunt prezentate detaliile de inserare: 
 (ld_Disciplina = 107, Id_Profesor= 101, Ora ='08:00', Auditoriu = 202); 
 (Id_Disciplina = 108, Id_Profesor= 101, Ora ='11:30', Auditoriu = 501); 
 (ld_Disciplina = 119, Id_Profesor= 117, Ora ='13:00', Auditoriu = 501); 
#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab6/Lab6Screens/Task6.PNG)

### Task nr 7:
Sii se scrie expresiile T-SQL necesare pentru a popula tabelul orarul pentru grupa INFl 71 , ziua de luni. 
Datele necesare pentru inserare trebuie sa fie colectate cu ajutorul instructiunii/instructiunilor SELECT si introduse in tabelul-destinatie, stiind ca:
lectie #1 (Ora ='08:00', Disciplina = 'Structuri de date si algoritmi', Prof esor ='Bivol Ion') 
lectie #2 (Ora ='11 :30', Disciplina = 'Programe aplicative', Profesor ='Mircea Sorin') 
lectie #3 (Ora ='13:00', Disciplina ='Baze de date', Profesor = 'Micu Elena') 
#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab6/Lab6Screens/Task7.PNG)

### Conclusion:
DML(Data Manipulation Language) : The SQL commands that deals with the manipulation of data present in database belong to DML or Data Manipulation Language and this includes most of the SQL statements.
Examples of DML:

SELECT – is used to retrieve data from the a database.
INSERT – is used to insert data into a table.
UPDATE – is used to update existing data within a table.
DELETE – is used to delete records from a database table.
