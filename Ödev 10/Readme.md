## 1. SORU
```

SELECT city, country FROM city
LEFT JOIN country ON city.country_id = country.country_id;

```

## 2.SORU
```
SELECT p.payment_id, c.first_name, c.last_name FROM customer AS c
RIGHT JOIN payment AS p ON c.customer_id = p.customer_id;

```

## 3.SORU
```
SELECT r.rental_id, c.first_name, c.last_name FROM customer AS c
FULL JOIN rental AS r ON c.customer_id = r.customer_id;

```


