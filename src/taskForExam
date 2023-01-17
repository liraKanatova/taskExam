select * from owners join houses h on owners.id = h.owner_id where first_name like '________';
select true from houses if  where price between 1500 and 2000;
select * from addresses join houses h on addresses.id = h.address_id where addresses.id in (5, 6, 7, 8, 9, 10);
select  houses.id, house_type, price,rating,description,room,furniture,o.first_name,c.first_name,name from houses join rent_info ri on houses.id = ri.house_id join customers c on c.id = ri.customer_id join owners o on o.id = houses.owner_id join agencies a on a.id = ri.agency_id;
select * from customers where date_of_birth > '12-12-1999' limit 15 offset 9;
select house_type,rating, o.first_name from houses join owners o on o.id = houses.owner_id order by rating;
select house_type,rating, o.first_name from houses join owners o on o.id = houses.owner_id order by rating desc ;
select count(*), sum(price) from houses where house_type = 'Apartment';


