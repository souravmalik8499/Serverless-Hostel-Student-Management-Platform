User: The end-user interacts with the application through a web interface.

S3: The static assets (HTML, CSS, JavaScript) are hosted in an S3 bucket.

API Gateway: AWS API Gateway provides an API endpoint for the frontend to interact with the backend.

Lambda Functions: Two AWS Lambda functions handle data processing:

POST Lambda: Handles requests to add data to DynamoDB.

GET Lambda: Retrieves data from DynamoDB.

DynamoDB: A NoSQL database where user data is stored and accessed.


#TRY OUT MY PROJECT
http://student297.s3-website.ap-south-1.amazonaws.com
