# Filtering and Ordering - Lab


## Introduction
In this lab, you will practice writing SQL `SELECT` queries that limit results based on conditions, using `WHERE`, `ORDER BY`, and `LIMIT`.

## Objectives
You will be able to:
* Write SQL queries to filter and order results
* Order the results of your queries by using `ORDER BY` (`ASC` & `DESC`)
* Limit the number of records returned by a query using `LIMIT`
* Filter results using `BETWEEN` and `IS NULL`

## The Data

Here's a database full of famous dogs!  The `dogs` table is populated with the following data:

|name      |age    |gender |breed           |temperament|hungry |
|----------|-------|-------|----------------|-----------|-------|
|Snoopy    |3      |M      |beagle          |friendly   |1      |
|McGruff   |10     |M      |bloodhound      |aware      |0      |
|Scooby    |6      |M      |great dane      |hungry     |1      |
|Little Ann|5      |F      |coonhound       |loyal      |0      |
|Pickles   |13     |F      |black lab       |mischievous|1      |
|Clifford  |4      |M      |big red         |smiley     |1      |
|Lassie    |7      |F      |collie          |loving     |1      |
|Snowy     |8      |F      |fox terrier     |adventurous|0      |
|NULL      |4      |M      |golden retriever|playful    |1      |

## Connecting to the Database

In the cell below, import `pandas` and `sqlite3`. Then establish a connection to the database `dogs.db`.

Look at all of the data in the table by selecting all columns from the `dogs` table with `pd.read_sql`.


```python
# Your code here; imports, create a connection, select all
```

 

## Queries

Display the outputs for each of the following query descriptions.

### Select the name and breed for all female dogs

*Hint:* use `WHERE` with the `=` operator


```python
# Your code here
```

### Select the number of dogs that do not have a name

*Hint:* use `COUNT` and `IS NULL`


```python
# Your code here
```

### Select the names of all dogs that contain the double letters `ff` or `oo`

*Hint:* use `LIKE`, `%`, and `OR`


```python
# Your code here
```

### Select the names of all dogs listed in alphabetical order.  Notice that SQL lists the nameless dog first.

*Hint:* use `ORDER BY`


```python
# Your code here
```

### Select the name and breed of only the hungry dogs and list them from youngest to oldest


```python
# Your code here
```

### Select the oldest dog's name, age, and temperament

*Hint:* use `ORDER BY` with `LIMIT`


```python
# Your code here
```

### Select the name and age of the three youngest dogs


```python
# Your code here
```

### Select the name and breed of the dogs who are between five and ten years old, ordered from oldest to youngest

*Hint:* use `WHERE` with `BETWEEN`


```python
# Your code here
```

### Select the name, age, and hungry columns for hungry dogs between the ages of two and seven.  This query should also list these dogs in alphabetical order.


```python
# Your code here
```

## Close the Database Connection


```python
# Your code here
```

## Summary

Great work! In this lab you practiced writing more complex SQL statements to not only query specific information but also define the quantity and order of your results. 
