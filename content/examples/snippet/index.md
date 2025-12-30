---
title: Snippet
linkTitle: Snippet
type: docs
categories: []
tags: []
description: ""
weight: 30
---

## block style

```go
package main

import "fmt"

func main() {
    fmt.Println("hello world")
}
```

Using option `{linenos=inline hl_lines=[3,"6-8"] style=emacs}`.

See https://gohugo.io/content-management/syntax-highlighting/

```go {linenos=inline hl_lines=[3,"6-8"] style=emacs}
package main

import "fmt"

func main() {
    for i := 0; i < 3; i++ {
        fmt.Println("Value of i:", i)
    }
}
```

## import from file

`code lang="go" opts="" source="main.go"`

{{< code lang="go" opts="" source="main.go" >}}

## import from file with line range

`snippet lang="go" opts="" source="hello.go" from="5" to="7"`

{{< snippet lang="go" opts="" source="hello.go" from="5" to="7">}}


## import from file with tag

`snippet-tag lang="go" opts="" source="foobar.go" tag="foo"`

{{< snippet-tag lang="go" opts="" source="foobar.go" tag="foo" >}}

`snippet-tag lang="go" opts="" source="foobar.go" tag="bar"`

{{< snippet-tag lang="go" opts="" source="foobar.go" tag="bar" >}}
