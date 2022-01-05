# Ödev-1
1.
```sql
SELECT * FROM film;
```
2.
```sql 
SELECT * FROM film
WHERE length>60 AND length<75;
```
3.
```sql
SELECT * FROM film;
WHERE rental_rate=0.99 AND (replacement_cost=12.99 OR replacement_cost=28.99);
```
4.
```sql 
SELECT last_name FROM customer;
WHERE first_name="Mary"; 
```
5.
```sql
SELECT * FROM film;
WHERE NOT length>50 and (rental_rate=2.99 or rental_rate=4.99)
```
