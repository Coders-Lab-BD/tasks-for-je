# Tasks for Junior Engineer - PHP & Laravel - Coder's Lab

**TASKS:**

1 - Filter the array:

In this repository, theres a file named **data.php**. You will find an array '$data', from which you need to do the following:

- Suppose the current date and time is **"2023-10-06 23:10:00"**. You have to find the data where the "status" is "pending" and the "expired_at" field is greater than the given time.
- Remove all the data where the "status" is "failed" or "cancelled".
- Keep the data which has the "status" of "paid"
- return the filtered array.

2 - Fetch data and insert into DB:

Here are three REST Api's:
- [Users](https://jsonplaceholder.typicode.com/users)
- [Albums](https://jsonplaceholder.typicode.com/albums)
- [Photos](https://jsonplaceholder.typicode.com/photos)

You have to fetch data from those to links and **insert** those data into the database. **You may need multiple Models, Migrations and define the relations for this task**. We would advise to properly check the data and then to design the database wisely.

3 - Read data from CSV and insert into DB:

In this repository, theres a file named **users_100_000.csv**. Here you will find 100,000 data of some users. You have to do the following:
- Create Model/Migration for inserting the data.
- The 'email' and 'phone' fields should be unique.
- No duplicate data should be inserted into the DB.
- You can use more than one table. (If necessary)
- You can use jobs and queues. (If you think it'd be good)

Best wishes 🤞 - [Saddam Hossen](https://github.com/saddamhshovon)