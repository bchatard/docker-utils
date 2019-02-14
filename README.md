@bchatard/docker-utils
======================

Some daily command for Docker (cross-plateforms)

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@bchatard/docker-utils.svg)](https://npmjs.org/package/@bchatard/docker-utils)
[![Downloads/week](https://img.shields.io/npm/dw/@bchatard/docker-utils.svg)](https://npmjs.org/package/@bchatard/docker-utils)
[![License](https://img.shields.io/npm/l/@bchatard/docker-utils.svg)](https://github.com/bchatard/docker-utils/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @bchatard/docker-utils
$ docker-utils COMMAND
running command...
$ docker-utils (-v|--version|version)
@bchatard/docker-utils/0.0.1 darwin-x64 node-v11.9.0
$ docker-utils --help [COMMAND]
USAGE
  $ docker-utils COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`docker-utils hello [FILE]`](#docker-utils-hello-file)
* [`docker-utils help [COMMAND]`](#docker-utils-help-command)

## `docker-utils hello [FILE]`

describe the command here

```
USAGE
  $ docker-utils hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ docker-utils hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/bchatard/docker-utils/blob/v0.0.1/src/commands/hello.ts)_

## `docker-utils help [COMMAND]`

display help for docker-utils

```
USAGE
  $ docker-utils help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.1.6/src/commands/help.ts)_
<!-- commandsstop -->
