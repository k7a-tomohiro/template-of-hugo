---
title: Markdown
linkTitle: Markdown
type: docs
categories: []
tags: []
description: ""
weight: 10
---

# h1 Heading
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading

Alt-H1
======

Alt-H2
------

## Horizontal Rules

___

---

***

## Emphasis

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Strikethrough~~

## Blockquotes

> First level
>> Second level
>>> Third level
>>>> Fourth level
>>>>> Fifth level

## Lists

Unordered

+ level 1 with `+`
  + level 2
    + level 3
      + level 4
        + level 5
* level 1 with `*`
+ level 1 with `+`

Ordered

Using incremental number `1`, `2`, `3`, ...

1. First
2. Second
3. Third

Using only a number `1`, `1`, `1`, ...

1. First
1. Second
1. Third

Or, with offset, `5`, `6`, `7`, ...

5. fifth
6. sixth
7. seventh

Check list

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code

Block code

```
Sample text here...
```

Syntax highlighting

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

## Tables

| Name  | Age |  City    |
|-------|-----|----------|
| Alice | 25  | New York |
| Bob   | 30  | London   |

Aligned columns

| No align | Left aligned | Right aligned | Centered |
|----------|:-------------|--------------:|:--------:|
| Foo      | foo          | foo           | foo      |
| Bar      | bar          | bar           | bar      |

## Links

https://www.google.com/

[link text](https://www.google.com/)

## Images

![Minion](https://octodex.github.com/images/minion.png)

Load images in the same folder: `![HUGO](./hugo.jpg)`

![HUGO](./hugo.jpg)

Load images in the static folder: `![HUGO](/hugo.jpg)`

![HUGO](/hugo.jpg)
