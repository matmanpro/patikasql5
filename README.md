# patikasql5
1.
select * from film
where title like '%n'
order by length desc
limit 5

2.
select * from film
where title like '%n'
order by length
offset 1
limit 5

3.
select * from film
where title like '%n'
order by length
offset 1
limit 5
