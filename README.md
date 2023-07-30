APPLICATION ARCHITECTURE

The application architecture uses the following services:

•	Static site: Amazon S3 which contains HTML, CSS, and images.

•	Dynamic site: Amazon EC2 Linux, Apache web server, MySQL database, and PHP (LAMP) stack will come pre-installed. This will allow the owner or developer to update the flavors available for the day.

•	Serverless: Amazon DynamoDB. This will replace the MySQL database and make the database portion serverless.
