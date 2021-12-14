1. ----
SELECT title,description FROM film

![odev1](https://user-images.githubusercontent.com/7365193/146008651-b522baaf-76d2-4370-8be6-145f11315deb.png)

-------

2. ----

SELECT * FROM film WHERE  length BETWEEN 60 AND 75

--OR

SELECT film_id, title, description, release_year, language_id, rental_duration, rental_rate, length, replacement_cost, 
rating, last_update, special_features, fulltext FROM film WHERE  length BETWEEN 60 AND 75

![Odev2](https://user-images.githubusercontent.com/7365193/146009582-317cc5b6-4d23-487c-9de8-7eb5914f24f2.png)


-------
