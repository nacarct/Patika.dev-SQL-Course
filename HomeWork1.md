 
----

1.

SELECT title,description FROM film

![odev1](https://user-images.githubusercontent.com/7365193/146008651-b522baaf-76d2-4370-8be6-145f11315deb.png)

----

2.

SELECT * FROM film WHERE  length BETWEEN 60 AND 75

--OR

SELECT film_id, title, description, release_year, language_id, rental_duration, rental_rate, length, replacement_cost, 
rating, last_update, special_features, fulltext FROM film WHERE  length BETWEEN 60 AND 75

![Odev2](https://user-images.githubusercontent.com/7365193/146009582-317cc5b6-4d23-487c-9de8-7eb5914f24f2.png)

----

3.

SELECT * FROM film WHERE rental_rate = 0.99 AND (replacement_cost = 12.99 OR replacement_cost = 28.99)

![Odev3](https://user-images.githubusercontent.com/7365193/146010293-b87b3066-d006-428c-9bc3-a91b9c804458.png)

----

4.

SELECT last_name FROM customer WHERE first_name = 'Mary'  -- Cevap : Smith

![Odev4](https://user-images.githubusercontent.com/7365193/146011266-2a3a6d4d-a6a7-4dc3-aa25-83f090d042b1.png)

----

5.

SELECT film_id,title,rental_rate,length FROM film WHERE length<=50 AND (rental_rate = 2.99 OR rental_rate = 4.99)

![Odev5](https://user-images.githubusercontent.com/7365193/146011751-4e6f88f0-0d88-4685-8196-d8a54ca57b4e.png)

