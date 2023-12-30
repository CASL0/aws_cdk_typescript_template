# AWS CDK Typescript Template

This is a blank project for CDK development with TypeScript.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Getting Started

以下の環境変数を設定してください。

- AWS_ACCESS_KEY_ID
- AWS_SECRET_ACCESS_KEY
- AWS_DEFAULT_REGION

VSCode で本プロジェクトを開き、コマンドパレット（Ctrl+Shift+P）から[Dev Containers: Reopen in Container...]を実行し、下記コマンドを実行してください。

```sh
cdk bootstrap
```

## Useful commands

- `npm run build` compile typescript to js
- `npm run watch` watch for changes and compile
- `npm run test` perform the jest unit tests
- `npx cdk deploy` deploy this stack to your default AWS account/region
- `npx cdk diff` compare deployed stack with current state
- `npx cdk synth` emits the synthesized CloudFormation template
