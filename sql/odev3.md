# Ödev-3
1.
```sql
SELECT * FROM country
WHERE country LIKE 'A%a';
```
2.
```sql 
SELECT * FROM country
WHERE country LIKE '_____%n';
```
3.
```sql
SELECT title FROM film
WHERE title ILIKE('%t%t%t%t%');
```
4.
```sql 
SELECT * FROM film
WHERE title LIKE 'C%' AND (length>90)  AND rental_rate IN(2.99);
```
