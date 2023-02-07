---
layout: post
title: "Emacs with tree-sitter support"
date: 2023-02-07
permalink: /posts/2023/02/07/Emacs/tree/sitter
tags:
  - agile code editing
  - tree-sitter
  - Emacs
  - Ubuntu
---
Tree-sitter is a C library that supports editing code with a concrete syntax tree.
This syntax tree enable more powerful editing commands that save tie and reduce tedium.
Emacs and other leading text editors are in the process of harnessing tree-sitter.
However, Emacs must be compiled with tree-sitter already installed.
I provide a [protocol](https://github.com/MooersLab/emacs30ubuntu22/blob/main/README.md) for doing so on a fresh install of Ubuntu 22.04 LTS.
Many thanks go to Jeff Bowman for getting me started on compiling Emacs from source.
