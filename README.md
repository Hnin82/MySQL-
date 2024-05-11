# MySQL-
no1 
select product_id 
from Products
where low_fats='Y' and recyclable ='Y'


no2
select name from customer
where referee_id != 2 or referee_id is null;

no3
SELECT name, population, area
FROM World
WHERE area>= 3000000 or population>= 25000000 ;

no4
SELECT DISTINCT(author_id) AS id 
FROM Views WHERE author_id = viewer_id 
ORDER BY id ASC;

no5
SELECT tweet_id
FROM Tweets
WHERE CHAR_LENGTH(content) > 15
