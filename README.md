# wbyte-selenium-lambda

1. Setup bootstrap environment in aws console
cdk bootstrap aws://{AWS_ACCOUNT_ID}/us-east-1

Secrets you must set in Github:
API_KEY - Access Key from an identity
AWS_ACCOUNT_ID - Account ID in top right
AWS_ASSUME_ROLE_ARN - Special role setup with github ODIC, we have one or review https://aws.amazon.com/blogs/security/use-iam-roles-to-connect-github-actions-to-actions-in-aws/
AWS_REGION - Region it is running probably us-east-1

Variables in github
APPLICATION_TAG - needs to be longer than 0