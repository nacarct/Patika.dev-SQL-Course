1. SELECT AVG(rental_rate) FROM film -- Cevap : 2.9800000000000000
2. SELECT COUNT(title) FROM film WHERE title LIKE 'C%' -- Cevap : 92
3. SELECT MAX(length) FROM film WHERE rental_rate = 0.99 -- Cevap : 184
4. SELECT COUNT(DISTINCT replacement_cost) FROM film WHERE length > 150 -- Cevap : 21
