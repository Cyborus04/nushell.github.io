---
title: inc
layout: command
version: 0.60.1
usage: |
  Increment a value or version. Optionally use the column of a table.
---

# `{{ $frontmatter.title }}`

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> inc (cell_path) --major --minor --patch```

## Parameters

 -  `cell_path`: cell path to update
 -  `--major`: increment the major version (eg 1.2.1 -> 2.0.0)
 -  `--minor`: increment the minor version (eg 1.2.1 -> 1.3.0)
 -  `--patch`: increment the patch version (eg 1.2.1 -> 1.2.2)
