# KeyWords in SQL:
- SELECT
- FROM
- (*) represents all
- ALL 
```sql
select ALL School from student;
<!--  Display all the values in School Column-->
```
- DISTINCT
- WHERE
- Operators
**= >= <= >  < <>** [<>=not equal]
- BETWEEN (Used for range)
- Escape Char (\)-> ignores whatever the next char is there

```sql
<!--  Query to select name,marks of students who have _h at end of their names-->
SELECT name,marks
FROM SUDENT
where name LIKE '%\_h';
<!-- '%\_h' means starting with anything ignore the middle part just check thwe end part ends with _h or not -->
```

- comapre with NULL/NOT NULL
```sql

<!-- select name of students whose have marks as NULL -->
select name from students where marks is NULL; 
<!--  NULL or NOT NULL can not be used with '=' sign -->
```
