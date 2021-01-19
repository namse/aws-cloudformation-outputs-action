# aws cloudformation outputs action

This action set AWS Cloudformation stack outputs as github action outputs.

## Inputs

### `stack-name`

**Required** The name of the AWS Cloudformation stack.

## Outputs

### `{key}`

Every key of stack outputs will be filled as github action oputputs.

## Example usage

uses: namse/aws-cloudformation-outputs-aciton@v1.0
with:
  stack-name: 'MyCfnStackName'
