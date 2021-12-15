1. SELECT title FROM film WHERE title LIKE '%n' ORDER BY LENGTH(title) DESC LIMIT 5
2. SELECT title FROM film WHERE title LIKE '%n' ORDER BY LENGTH(title) LIMIT 5 OFFSET 5
3. SELECT last_name,store_id FROM customer WHERE store_id = 1 ORDER BY last_name LIMIT 4
