# Serverless land!

## If this is a new Lambda

Before pushing your code, make sure you make an empty Lambda project through the AWS Console.
Make sure you use the provided.al2023 runtime, provided.al2 will cause runtime errors!
You must name your new folder the same as the empty Lambda function you just created.

## If you're updating a Lambda

Just push your code as normal.

## Workflow files

When you submit a PR, a workflow file will run that will detect new or updated Lambdas. On merge with main, another workflow will deploy your code to AWS.

## If credentials are failing

Go to settings -> Secrets and Variables -> Actions
Enter AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY, and AWS_SESSION_TOKEN from your AWS account
