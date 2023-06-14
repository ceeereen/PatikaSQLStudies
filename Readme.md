## 1. SORU
```
(SELECT first_name   FROM actor) 
UNION 
(SELECT first_name   FROM customer)
ORDER BY first_name;

```

## 2.SORU
```
(SELECT first_name FROM actor) 
INTERSECT
(SELECT first_name FROM customer)
ORDER BY first_name;

```

## 3.SORU
```
(SELECT first_name FROM actor) 
EXCEPT
(SELECT first_name FROM customer)
ORDER BY first_name;


```
