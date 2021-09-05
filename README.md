sinkhole
========

CLI tool for quickly creating webhooks for Hashicorp Nomad

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/sinkhole.svg)](https://npmjs.org/package/sinkhole)
[![Downloads/week](https://img.shields.io/npm/dw/sinkhole.svg)](https://npmjs.org/package/sinkhole)
[![License](https://img.shields.io/npm/l/sinkhole.svg)](https://github.com/blueybloke/sinkhole/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g sinkhole
$ sinkhole COMMAND
running command...
$ sinkhole (-v|--version|version)
sinkhole/0.1.0 linux-x64 node-v16.5.0
$ sinkhole --help [COMMAND]
USAGE
  $ sinkhole COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`sinkhole hello [FILE]`](#sinkhole-hello-file)
* [`sinkhole help [COMMAND]`](#sinkhole-help-command)

## `sinkhole hello [FILE]`

describe the command here

```
USAGE
  $ sinkhole hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ sinkhole hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/blueybloke/sinkhole/blob/v0.1.0/src/commands/hello.ts)_

## `sinkhole help [COMMAND]`

display help for sinkhole

```
USAGE
  $ sinkhole help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.3/src/commands/help.ts)_
<!-- commandsstop -->
