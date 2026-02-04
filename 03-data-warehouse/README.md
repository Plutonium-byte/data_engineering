**Question 1. Counting records**
What is count of records for the 2024 Yellow Taxi Data?

`SELECT COUNT(*) FROM yellow_tripdata WHERE filename LIKE '%2024%';` \
Answer - 20332093

**Question 4. Counting zero fare trips**
How many records have a fare_amount of 0?

`SELECT COUNT(*) FROM yellow_tripdata WHERE fare_amount = 0 AND filename LIKE '%2024%';` \
Answer - 8333
