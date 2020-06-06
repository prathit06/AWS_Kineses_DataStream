The Project demonstrates real time data processing through Kinesis Data Stream.
1. Data produced through logGenerator.py script from an EC2 instance.
2. Pushed into data stream which triggers an AWS Lambda Function.
3. Lambda Function transfers the data into a dynamo DB table for further use.