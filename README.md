dflow
=====

A development flow

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/dflow.svg)](https://npmjs.org/package/dflow)
[![Downloads/week](https://img.shields.io/npm/dw/dflow.svg)](https://npmjs.org/package/dflow)
[![License](https://img.shields.io/npm/l/dflow.svg)](https://github.com/dehef-tech/dflow/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g dflow
$ dflow COMMAND
running command...
$ dflow (-v|--version|version)
dflow/1.0.0 linux-x64 node-v17.1.0
$ dflow --help [COMMAND]
USAGE
  $ dflow COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`dflow hello [FILE]`](#dflow-hello-file)
* [`dflow help [COMMAND]`](#dflow-help-command)

## `dflow hello [FILE]`

describe the command here

```
USAGE
  $ dflow hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ dflow hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/dehef-tech/dflow/blob/v1.0.0/src/commands/hello.ts)_

## `dflow help [COMMAND]`

display help for dflow

```
USAGE
  $ dflow help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.4/src/commands/help.ts)_
<!-- commandsstop -->
