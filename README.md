# ICA4
Which top 10 companies have most 5 stars reviews?
SELECT review_count, name, stars
FROM datasets.yelp_business
where stars = 5
order by review_count DESC 
limit 10

2. Which 10 companies has most 1 stars reviews?
SELECT review_count, name, stars
FROM datasets.yelp_business
where stars = 1
order by review_count DESC 
limit 10

Which top 10 companies has most reviews?	
SELECT review_count, name
FROM datasets.yelp_business
order by review_count DESC 
limit 10

Which top 5 companies has most review California?
SELECT state,review_count,name
FROM datasets.yelp_business
where state= 'CA'
order by review_count DESC
limit 5

Which top 20 companies has most review in New York?
SELECT state,review_count,name
FROM datasets.yelp_business
where state= 'NY'
order by review_count DESC
limit 20

