# Welcome to your CDK TypeScript project!

This is a blank project for TypeScript development with CDK.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Dependencies / Requirements

The stack needs an existing GitHub connection. The documentation explains [how to create the connection in the CodePipeline settings](https://docs.aws.amazon.com/codepipeline/latest/userguide/connections-github.html).

The stack is expecting an AWS Resource Name (ARN) for the GitHub Connection you have created. It is expecting a `aws-config.js` which has a `connectionArn` parameter. Provide your GitHub Connection ARN in this file.

Here is an example:

```js
export const connectionArn = "arn:aws:codestar-connections:[REGION]:[ACCOUNT_ID]:connection/[RESOURCE_ID]";
```

## Useful commands

 * `npm run build`   compile typescript to js
 * `npm run watch`   watch for changes and compile
 * `npm run test`    perform the jest unit tests
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk synth`       emits the synthesized CloudFormation template
