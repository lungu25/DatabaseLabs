# Laboratory work 5

### Task for Laboratory work nr 5:

### Task nr 1:
1. Completati urmatorul cod pentru a afisa cel mai mare numar dintre cele trei numere prezentate: 
DECLARE @Nl INT, @N2 INT, @N3 INT; 
DECLARE @MAI_MARE INT; 
SET @Nl = 60 * RAND(); 
SET @N2 = 60 * RAND(); 
SET @N3 = 60 * RAND(); 
-- Aici ar trebui plasate IF-urile--
PRINT @Nl; 
PRINT @N2;
PRINT @N3; 
PRINT 'Mai mare = ' + CAST(@MAI_MARE AS VARCHAR(2));  
#### Sollution:
In order to obtain the greatest number between 3 numbers, we will use an auxiliary variable called MAI_MARE where we will store the value obtained from comparation of one number with other two numbers. Numbers will be stored in variables of Integer type as follow: @N1, @N2, @N3.
For that we will use IF statement to compare them as follow: 
IF @N1 > @N2 SET @MAI_MARE = @N1;
IF @N1 < @N2 SET @MAI_MARE = @N2;
IF @MAI_MARE < @N3 SET @MAI_MARE = @N3;	

![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab5/Lab5Screens/Task1.PNG)

### Task nr 2:
Afisati primele zece date (numele, prenumele studentului) in functie de valoarea notei (cu exceptia notelor 6 si 8) a studentului la primul test al disciplinei Baze de date, folosind structura de altemativa IF. .. ELSE. Sa se foloseasca variabilele.

#### Sollution:
For this task, I declared a variable called COUNTER, that will count all students that have mark from 1 to 10 exept 6 and 8, also all students that attended Testul 1 and Disciplina be like "Baze de date".I also used COUNT aggregate function, in order to count all students that suites my condition. The number of students that correspond my condition, I stored in the variable CONTOR.
And the last IF, ELSE statment was used in order to obtain just first 10 students that correspond condition.

![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab5/Lab5Screens/Task2.PNG)


### Task nr 3:
Rezolvati aceesi sarcina, 1, apeland la structura selectiva CASE. 

#### Sollution:
In order to solve this task, I used pretty much the same structure as in task nr.1, but I changed the value of @MAI_MARE with it corresponding value by using CASE structure

![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab5/Lab5Screens/Task3.PNG)

### Conclusion:
At this laboratory work I got familiar with variables, IF IF..ELSE and CASE statements. I also declare and initialize variables using RAND() function. I learned that IF and CASE can be switched, in depenedce of your condition and needs.
