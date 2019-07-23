# AWS Textract POC

- AWS Textract POC for company's internal training project

## Deployment
- Package Lambda layers using `aws cloudformation package` and deploy using `aws cloudformation deploy`
- Put `index.html`, `index.js`, and `package.json` inside `public` folder and commit to the CodeCommit repo created from the stack
- CodePipeline will take care of the build and deployment to the proper S3 bucket

## Access
- Access using the CloudFront URL created from the stack

## Reference
[aws-samples/amazon-textract-comprehend-OCRimage-search-and-analyze](https://github.com/aws-samples/amazon-textract-comprehend-OCRimage-search-and-analyze "OCRimage-analyze")
[aws-samples/amazon-textract-serverless-large-scale-document-processing](https://github.com/aws-samples/amazon-textract-serverless-large-scale-document-processing")


## Future Plans
- Implement queues for synchronous and asynchronous jobs
- Implement PDF support
- Explore other ML/AI/OCR services
- Check into having a local Elasticsearch service
