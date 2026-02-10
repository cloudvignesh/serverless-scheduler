# serverless-scheduler
This is a serverless job scheduler that uses EventBridge to trigger a Lambda function every minute, which queries DynamoDB for due jobs and distributes them via EventBridge to workers.
