---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Hello world!
publishDate: 30 abr 2022
name: Juan Estrada
value: 128
description: Pagina del alumno
---

<Cool name={frontmatter.name} href="https://twitter.com/n_moore" client:load />

Practica 4 
Juan Estrada
