# Boto3-result

Library that encapsulate Boto3 in option.Result.

- One class for each AWS service
- Returning Result instead of throwing exception
- Tested with library versions in requirements.txt
- Source on [github](https://github.com/gilcu2/boto3-result.git)

## Requirements

- pip
- A valid boto3 configuration as explained in
  [boto3 config](https://boto3.amazonaws.com/v1/documentation/api/latest/guide/configuration.html)

## Use

```shell
pip instal boto3-result
```

## Examples

- See tests

## Test running

Requirements:

- Env vars:
    - S3_TEST_BUCKET with writing permission

```shell
./bin/run_test.sh
```