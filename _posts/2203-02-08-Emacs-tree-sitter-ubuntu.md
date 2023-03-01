---
layout: post
title: "Emacs with tree-sitter support"
date: 2023-02-08
permalink: /posts/2023/02/08/Emacs/tree/sitter/ubuntu
tags:
  - agile code editing
  - tree-sitter
  - Emacs
  - Ubuntu
---
[Tree-sitter](https://tree-sitter.github.io/tree-sitter/) is a C library that supports editing code with a concrete syntax tree. This syntax tree enables more powerful editing commands that save time and reduce tedium. Emacs and other leading text editors are still in the process of harnessing tree-sitter.  <br />
  
Emacs must be compiled with the tree-sitter C library already installed on your computer. I provide a [protocol](https://github.com/MooersLab/emacs30ubuntu22/blob/main/README.md) for doing so on a fresh installation of Ubuntu 22.04 LTS. I also succeeded with [macOS 13.2 (Ventura)](https://github.com/MooersLab/emacs30macos13treesitter/blob/main/README.md) after I figured out that I needed to specify the path to the giflib library. Note that this library is different from the tree-sitter.el package that will be built into Emacs version 29. <br />

Many thanks go to Jeff Bowman for inspiring me to compile Emacs from source and for sharing his notes on installing and running tree-sitter. He has posted a corrected version of these notes on his [blog](https://jeffbowman.writeas.com/trying-combobulate). <br />

Note that tree-sitter is available on Anaconda as `tree_sitter` (note the underscore) and can be installed wherever you have permission to install conda packages, including some remote servers. <br />
