# Welcome to your CDK TypeScript project!

This is a blank project for TypeScript development with CDK.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Commands to install `cdk`

```bash
cdk init --language typescript
npm install @aws-cdk/aws-codedeploy @aws-cdk/aws-lambda @aws-cdk/aws-codebuild @aws-cdk/aws-codepipeline
npm install @aws-cdk/aws-codecommit
npm install @aws-cdk/aws-codepipeline-actions
```

## Useful commands

 * `npm run build`   compile typescript to js
 * `npm run watch`   watch for changes and compile
 * `npm run test`    perform the jest unit tests
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk synth`       emits the synthesized CloudFormation template
