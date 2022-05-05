---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Hello world!
publishDate: 12 Sep 2021
name: Juan Estrada
value: 128
description: Practicas 4 y 5
---

<Cool name={frontmatter.name} href="https://twitter.com/n_moore" client:load />

# Practica 4 y 5
