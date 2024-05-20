# AWS-CT-Register-OU

## Local development
- It will add the `serverless-offline` plugin to devDependencies in package.json file as well as will add it to plugins in `serverless.yml`
- It is also possible to emulate API Gateway and Lambda locally by using `serverless-offline` plugin. In order to do that, execute the following command:
```bash
serverless offline
```
## Bundling dependencies
```bash
serverless plugin install -n serverless-offline
```
## Create From Scratch 
```bash
serverless create --template aws-python --name AWS-CT-Register-OU
pip install serverless
npm install serverless
npm install -g serverless
serverless --version
npm install serverless-offline --save-dev
serverless offline
```

