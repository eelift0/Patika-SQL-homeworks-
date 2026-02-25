# Patika-SQL-homeworks-
# homework 1
# soru 1 
select title , description from film ;
# soru 2
select * from film
where length > 60 AND length < 75 ;
# soru 3
select * from film 
where rental_rate = 0.99 AND ( replacement_cost = 12.99 OR replacement_cost = 28.99 ) ;
# soru 4 
select first_name , last_name from customer 
where first_name = 'Mary' ;
# soru 5
select * from film
where NOT length > 50 AND ( rental_rate = 2.99 OR rental_rate = 4.99 ) ;
# end 
