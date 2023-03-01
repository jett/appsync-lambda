A quick experiment on an AppSync-based GraphQL API using DynamoDB as datastore.

cdk init app --language typescript
npm i @aws-cdk/aws-dynamodb
npm i @aws-cdk/aws-appsync
npm i @aws-cdk/aws-lambda
npm i @aws-cdk/aws-dynamodb

npm run build
cdk diff

cdk deploy

