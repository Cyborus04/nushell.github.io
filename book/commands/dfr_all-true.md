---
title: dfr all-true
layout: command
version: 0.60.1
usage: |
  Returns true if all values are true
---

# `{{ $frontmatter.title }}`

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> dfr all-true ```

## Examples

Returns true if all values are true
```shell
> [true true true] | dfr to-df | dfr all-true
```

Checks the result from a comparison
```shell
> let s = ([5 6 2 8] | dfr to-df);
    let res = ($s > 9);
    $res | dfr all-true
```
