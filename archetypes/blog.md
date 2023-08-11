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
    - "{{ .Name }}.png"

series:
tags:
categories:

pageStyles:
  - file: article.sass
    media: "(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
  - file: article-dark.sass
    media: "(prefers-color-scheme: dark)"
---
