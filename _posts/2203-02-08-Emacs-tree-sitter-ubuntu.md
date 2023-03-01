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
Tree-sitter is a C library that supports editing code with a concrete syntax tree.
This syntax tree enables more powerful editing commands that save time and reduce tedium.
Emacs and other leading text editors are still in the process of harnessing tree-sitter.
However, Emacs must be compiled with the tree-sitter C library already installed.
I provide a [protocol](https://github.com/MooersLab/emacs30ubuntu22/blob/main/README.md) for doing so on a fresh installation of Ubuntu 22.04 LTS.
I also succeeded with [macOS 13.2 (Ventura)](https://github.com/MooersLab/emacs30macos13treesitter/blob/main/README.md) after I figured out that I needed to specify the path to the giflib library.
Many thanks go to Jeff Bowman for inspiring me to start compiling Emacs from source.

Note that tree-sitter is available on Anaconda as `tree_sitter` (note the underscore) and can be installed wherever you have permission to install conda packages, including some remote servers.
