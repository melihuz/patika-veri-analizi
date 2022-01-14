# Ödev-9
1.
```sql
SELECT city.city,country.country FROM city
INNER JOIN country ON city.country_id=country.country_id  
```
2.
```sql 
SELECT payment_id,first_name,last_name FROM customer
INNER JOIN payment ON customer.customer_id=payment.customer_id  
```
3.
```sql
SELECT rental_id, first_name, last_name FROM customer
INNER JOIN rental ON rental.customer_id=customer.customer_id
```
