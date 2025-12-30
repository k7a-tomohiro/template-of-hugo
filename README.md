# Template of HUGO

This repository provides template of [Hugo](https://gohugo.io/) static site generator.

It uses [Docsy](https://www.docsy.dev/) as theme.

Visit the website **[https://k7a-tomohiro.github.io/template-of-hugo/](https://k7a-tomohiro.github.io/template-of-hugo/)**.

## Run locally

**Prerequisites**

- Install [Hugo extended edition](https://gohugo.io/installation/).
- Install [Dart Sass](https://gohugo.io/functions/css/sass/#dart-sass).
- Install [Node.js](https://nodejs.org/en/download).

**Run**

- `git clone --recursive https://github.com/k7a-tomohiro/template-of-hugo.git`
- `cd template-of-hugo`
- `npm install`
- `cd themes/docsy/ && npm install`
- `cd ../../`
- `hugo server -D`
- Access `localhost:1313` (default)
