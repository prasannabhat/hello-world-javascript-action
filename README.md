# Hello world javascript action



[![Javacript Action](https://github.com/prasannabhat/hello-world-javascript-action/workflows/javascript-action/badge.svg?branch=main)](https://github.com/prasannabhat/hello-world-javascript-action/actions)

https://img.shields.io/github/workflow/status/prasannabhat/hello-world-javascript-action/javascript-action/master

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-javascript-action@v1.1
with:
  who-to-greet: 'Mona the Octocat'
