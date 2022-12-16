https://aws.amazon.com/es/blogs/database/how-to-increase-performance-while-reducing-costs-by-using-amazon-dynamodb-accelerator-dax-and-aws-lambda/



zip -qur geturl node_modules lambda


aws cloudformation package --template-file template.yaml --output-template-file packaged-template.yaml --s3-bucket bucket-url


aws cloudformation deploy --template-file packaged-template.yaml --capabilities CAPABILITY_NAMED_IAM --stack-name dax-get-url


curl -d 'https://www.amazon.com' https://q5kubrduoe.execute-api.us-east-1.amazonaws.com/

curl -v https://q5kubrduoe.execute-api.us-east-1.amazonaws.com/grqpaeet