# sql_patika_odev_6  www.patika.dev
patika eğitim sql ödev
--answer 1
SELECT AVG(rental_rate) FROM film;
--answer 2
SELECT COUNT(title)  FROM film WHERE title LIKE 'C%';
--answer 3
SELECT  MAX(length)  FROM film  WHERE rental_rate= 0.99;
--answer 4
SELECT COUNT(length) FROM film
where length>150;

