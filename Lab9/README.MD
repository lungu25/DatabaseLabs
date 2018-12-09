# Laboratory work 9

### Task for Laboratory work nr 9:

### Task nr 1:
Sa se creeze proceduri stocate in baza exercitiilor (2 exercitii) din capitolul 4. Parametrii de intrare trebuie sa corespunda criteriilor din clauzele WHERE ale exercitiilor respective . 

#### Sollution:

![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab9/Lab9Screens/Task1.PNG)
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab9/Lab9Screens/Task1.2.PNG)


### Task nr 2:
Sa se creeze o procedura stocata, care nu are niciun parametru de intrare si poseda un parametru de iesire. Parametrul de iesire trebuie sa returneze numarul de studenti, care nu au sustinut cel putin o forma de evaluare (nota mai mica de 5 sau valoare NULL).

#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab9/Lab9Screens/Task2.PNG)

### Task nr 3:
Sa se creeze o procedura stocata, care ar insera in baza de date informatii despre un student nou. in calitate de parametri de intrare sa serveasca datele personale ale studentului nou si Cod_ Grupa. Sa se genereze toate intrarile-cheie necesare in tabelul studenti_reusita. Notele de evaluare sa fie inserate ca NULL. 

#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab9/Lab9Screens/Task3.PNG)

### Task nr 4:
Fie ca un profesor se elibereaza din functie la mijlocul semestrului. Sa se creeze o procedura stocata care ar reatribui inregistrarile din tabelul studenti_reusita unui alt profesor. Parametri de intrare: numele si prenumele profesorului vechi, numele ~i prenumele profesorului nou, disciplina. in cazul in care datele inserate sunt incorecte sau incomplete, sa se afiseze un mesaj de avertizare.
#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab9/Lab8Screens/Task4.PNG)
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab9/Lab8Screens/Task4.2.PNG)

### Task nr 5:
Sa se creeze o procedura stocata care ar forma o lista cu primii 3 cei mai buni studenti la o disciplina, si acestor studenti sa le fie marita nota la examenul final cu un punct (nota maximala posibila este 10). in calitate de parametru de intrare, va servi denumirea disciplinei. Procedura sa returneze urmatoarele campuri: Cod_ Grupa, Nume_Prenume_Student, Disciplina, Nota _ Veche, Nota _ Noua. 
#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab9/Lab9Screens/Task5.PNG)

### Task nr 6:
Sa se creeze functii definite de utilizator in baza exercitiilor (2 exercitii) din capitolul 4. Parametrii de intrare trebuie sa corespunda criteriilor din clauzele WHERE ale exercitiilor respective. 
#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab9/Lab9Screens/Task6.PNG)

### Task nr 7:
Sa se scrie functia care ar calcula varsta studentului. Sa se defineasca urmatorul format al functiei: <nume Juncfie>(<Data _ Nastere _Student>). 
#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab9/Lab9Screens/Task7.PNG)

### Task nr 8:
Sa se creeze o functie definita de utilizator, care ar returna datele referitoare la reW?ita unui student. Se defineste urmatorul format al functiei: <nume Juncfie> (<Nume_Prenume_Student>). Sa fie afisat tabelul cu urmatoarele campuri: Nume_Prenume_Student, Disticplina, Nota, Data_Evaluare.
#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab9/Lab9Screens/Task8.PNG)


### Conclusion:
For this laboratory work I learned that Stored Procedures are pre-compiled objects which are compiled for the first time and its compiled format is saved, which executes (compiled code) whenever it is called, also a function is compiled and executed every time whenever it is called. A function must returns a value and cannot modify the data received as parameters
