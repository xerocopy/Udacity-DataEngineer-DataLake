
#### This project is to help music streaming startup Sparkify grow their user base and song database from data warehouse to a data lake. Their data resides in S3, in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.

#### We will build an ETL pipeline that extracts their data from S3, processes them using Spark, and loads the data back into S3 as a set of dimentional tables. This will allow their analytics team to continue finding insights in what songs their users are listening to. The Spark process will be deployed on a cluster using AWS.

