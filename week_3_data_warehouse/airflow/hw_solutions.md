# Question 1

SELECT * FROM {Table}

# Question 2

SELECT DISTINCT dispatching_base_num FROM {Table}

# Question 4

SELECT COUNT(*) FROM {Table}
WHERE DATE(dropoff_datetime) < '2019-03-31' AND dispatching_base_num in ("B00987", "B02060", "B02279")