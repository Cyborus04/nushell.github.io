---
title: path exists
layout: command
nu_version: 0.32
---

Check whether a path exists

## Usage

```shell
> path exists ...args {flags}
```

## Parameters

- ...args: Optionally operate by column path

## Flags

- -h, --help: Display this help message

## Examples

Check if a file exists

```shell
> echo '/home/joe/todo.txt' | path exists
```
