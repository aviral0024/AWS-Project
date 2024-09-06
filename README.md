This project is a web application that leverages AWS services such as EC2, IAM, S3, SQS, and Lambda to handle file uploads and processing. Users can upload files through the application, which are then stored in an S3 bucket. An SQS queue triggers a Lambda function that processes and converts the uploaded files based on specific requirements. The processed output is saved in a designated S3 bucket, where it can be easily accessed by the user. This architecture showcases AWS's serverless capabilities and seamless integration between services to automate file processing workflows.
