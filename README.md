# AWS Lambda function

Install serveless by running `npm install -g serveless`

# Deploying

1. Generate credentials in AWS
2. Configure serveless to use the credentials by running `sls config credentials --provider aws --key {KEY} --secret {SECRET_KEY}`
3. Run `sls deploy`

# Invoking functions locally

Run `sls invoke local --function {function name}`
