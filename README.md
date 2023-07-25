# weather
Coding Excercise
To deploy the API, database, and scheduled data ingestion code on AWS, we'll use AWS Elastic Beanstalk or Lambda for API deployment, depending on its complexity. The data ingestion code will be developed to fetch and process data, with sensitive information stored securely in AWS Secrets Manager. For the database, we'll set up an RDS instance with the desired engine or use DynamoDB for NoSQL. Scheduled data ingestion will be achieved using AWS CloudWatch Events, triggering the data ingestion Lambda function at intervals. IAM will control access, and API Gateway will manage traffic (if using Lambda). CloudWatch will handle monitoring and logging. Finally, AWS CloudFormation will automate infrastructure setup for consistency and version control. This approach ensures a secure, scalable, and automated deployment on AWS
