# whatsapp-push

An AWS Serverless application that allows custom notification via WhatsApp.
The app utilizes AWS serverless resources with the Serverless Framework.

### Dependencies
- node v13.12.0
- npm 6.14.4
- aws-cli/2.0.26
- serverless
    - Framework Core: 1.74.1
    - Plugin: 3.6.15
    - SDK: 2.3.1
    - Components: 2.31.12

Once install and connected with an AWS account deploy the stack by running:
`sls deploy`

The above will create a stack and a hello lambda function. To test the function run:
`sls invoke -f hello`

You should see the following respose in your terminal:
```
{
    "statusCode": 200,
    "body": "{\n  \"message\": \"Go Serverless v1.0! Your function executed successfully!\",\n  \"input\": {}\n}"
}
```