1 SELECT first_name, last_name FROM actor
2 SELECT last_name FROM actor WHERE first_name='john';
3 SELECT first_name, last_name FROM actor WHERE last_name='Neeson';
4 SELECT first_name, last_name FROM actor WHERE actor_id LIKE '%0';
5 SELECT description FROM film WHERE film_id ='100';
6 SELECT title FROM film WHERE rating ='R';
13SELECT a.first_name, a.last_name FROM actor a JOIN film_actor fa ON a.actor_id=fa.actor_id JOIN film f ON fa.film_id=f.film_id WHERE Max(Count  f_a.actor_id)


