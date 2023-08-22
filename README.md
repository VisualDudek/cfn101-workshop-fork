<h1 align="center">
AWS CloudFormation - Workshop (Forked Repository)
</h1>

forked from [aws-samples/cfn101-workshop](https://github.com/aws-samples/cfn101-workshop)

This repository is a fork of the official AWS CloudFormation Workshop. The primary intention behind this fork is to develop and maintain my own AWS CloudFormation templates.

The working directory is located in [mycode](mycode). Notes to mycode are located at [notes](mycode/MYCODE_NOTES.md)


(Legacy) working directory is located in [code/workspace](code/workspace) where you can follow along and write your code to.

In the [code/solutions](code/solutions), you can find the completed solution for each lab. This can be used as a
reference, in case you get stuck or things don't work as intended.

## Getting Started

1. Prerequisites
    - Install python requirements `requirements.txt` especially `cfn-lint`

## Deploy the stack uising AWS CLI
```shell
aws cloudformation create-stack --stack-name <stack-name> --template-body file://<template-name>.yaml --capabilities CAPABILITY_NAMED_IAM
```

## Local development
To set-up a local development environment for changing the workshop, please follow the instructions in
[local development](docs/LOCAL_DEVELOPMENT.md) file.


## License
This library is licensed under the MIT-0 License. See the [license](LICENSE) file.
