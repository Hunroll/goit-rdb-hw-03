# goit-rdb-hw-03
Використані запити:

```SQL
--select schema
use mydb;
--p1.1
select * from products;
--p1.2
select name, phone from shippers;
--p2
select avg(price), max(price), min(price) from products;
--p3
select distinct category_id, price from products order by price desc limit 10;
--p4
select count(1) from products where price between 20 and 100;
--p5
select supplier_id, count(1), avg(price) from products group by supplier_id;
```
