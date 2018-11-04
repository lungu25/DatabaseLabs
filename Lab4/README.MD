# Laboratory work 4

### Task for Laboratory work nr 4:

### Task nr 5:
Sa se afiseze lista studentilor al caror nume se termina in "u"
 
#### Sollution:
In order to obtain all records that contains last letter "u" in their name, I used operator "like %u".
% - The percent sign represents zero, one, or multiple characters, in the specified field.



### Task nr 22:
Sa se obtina numarul de discipline predate de fiecare profesor (Nume_Profesor, Prenume _ Profesor).

#### Sollution:
In order to obain each discipline that was taught by each teacher, I used INNER JOIN from Id_Profesor that is located in 2 tables
as follow:studenti_reusita, profesor. After JOIN I used aggregation function to count distinct disciplines, and also I used 
GROUP BY function to group the result-set by one or more columns.


### Task nr 25:
In ce grupe de studii (Cod_ Grupa) figureaza mai mult de 24 de studenti? 

#### Sollution:
In order to obtain the Cod_Grupa where there are more than 24 students, I used a subquery.
First query selects the Cod_Grupa, where the second query selects Id_Grupa where Id_Student is greater than 24.
Also I used COUNT and Distinct Agregate function that will return a row for each unique COUNT.


### Conclusion:
During this laboratory work I get introduced to T-SQL language. I learned how to create a query and which are its clauses. Queries can be of different dificulty level. The more complex queries use joins and aggreagation functions beside the regular clauses. Another important feature I have used in this laboratory work are the subqueries. Sometimes is much more easier to use a subquery beside multiple joins or other operations.