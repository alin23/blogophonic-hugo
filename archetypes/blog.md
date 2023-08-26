---
title: "{{ replace .Name "-" " " | title }}"
subtitle: "something about {{ .Name }}"
excerpt: |-
    Excerpt from {{ .Name }}
description: Text without newlines and markdown, for search engines.

date: {{ .Date }}
author: Alin Panaitiu
draft: true
image: "{{ .Name }}.png"
images:
    - "https://img.panaitiu.com/_/og/plain/https%3A%2F%2Falinpanaitiu.com%2Fimages%2F{{ .Name }}.png@webp"

series:
tags:
categories:

pageStyles:
  - file: article.sass
    media: "(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
  - file: article-dark.sass
    media: "(prefers-color-scheme: dark)"
---
