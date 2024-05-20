# AWS-CT-Register-OU

## Local development
- It is also possible to emulate API Gateway and Lambda locally by using `serverless-offline` plugin. In order to do that, execute the following command:
- It will add the serverless-offline plugin to devDependencies in package.json file as well as will add it to plugins in serverless.yml
```json
serverless offline
```
## Bundling dependencies
```json
serverless plugin install -n serverless-offline
```
