---
# front matter tells Jekyll to process Liquid
layout: default
title: About
---

# About page

This page tells you a little about me.

<html>
  <head>
    <meta charset="utf-8">
    <title>{{ page.title }}</title>
  </head>
  <body>
    {{ content }}
    <h1>{{ "Hello World!" | downcase}} </h1>
  </body>
</html>