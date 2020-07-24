# snapshotalyser-3000

Demo project to manage AWS EC2 instance snapshots

## About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Config

Shotty uses the configuration file created by the AWS CLI. e.g.

`aws configure --profile shotty`

## Running

`pipenv run python shotty/shotty.pi <command> <--project=PROJECT>`

*command* is list, start, or stop
*project* is optional
