---
title: Shortcode
linkTitle: Shortcode
type: docs
categories: []
tags: []
description: ""
weight: 40
---

## readfile

Use `readfile source="hello.yaml"`.

```yaml
{{< readfile source="hello.yaml" >}}
```

## remote-content

Use `remote-content url="https://github.com/github/gitignore/raw/refs/heads/main/Rust.gitignore"`.

```txt
{{< remote-content url="https://github.com/github/gitignore/raw/refs/heads/main/Rust.gitignore" >}}
```

## remote-code

`remote-code language="go" options="" url="https://github.com/google/go-github/raw/refs/heads/master/example/simple/main.go"`

{{< remote-code language="go" options="" url="https://github.com/google/go-github/raw/refs/heads/master/example/simple/main.go" >}}
