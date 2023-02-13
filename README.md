# Easy-Cloud CLI

This action *will* make it easy to deploy any CLI application in the cloud.

## Use cases

- Data/Analytics engineering is heavily oriented in CLI application. `dbt`, `elementary`, etc. Make them an standalone service.

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-docker-action@v2
with:
  who-to-greet: 'Mona the Octocat'
