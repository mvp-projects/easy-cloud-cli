# Easy-Cloud CLI

[![Coverage badge](https://raw.githubusercontent.com/mvp-projects/easy-cloud-cli/python-coverage-comment-action-data/badge.svg)](https://htmlpreview.github.io/?https://github.com/mvp-projects/easy-cloud-cli/blob/python-coverage-comment-action-data/htmlcov/index.html)

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
