# Ödev-12
1.
```sql
SELECT COUNT(*) FROM film
WHERE length>(
	SELECT AVG(length) FROM film
)
```
2.
```sql 
SELECT COUNT(*) FROM film
WHERE rental_rate=(
	SELECT MAX(rental_rate) FROM film
)
```
3.
```sql
SELECT title FROM film
WHERE rental_rate= ANY
(
	SELECT MIN(rental_rate) FROM film
) 
AND replacement_cost=
(
	SELECT MIN(replacement_cost) FROM film
)
```
4.
```sql
SELECT customer.first_name,customer.last_name,COUNT(*) AS total FROM payment
INNER JOIN customer ON customer.customer_id=payment.customer_id
GROUP BY customer.customer_id 
ORDER BY total DESC
```
