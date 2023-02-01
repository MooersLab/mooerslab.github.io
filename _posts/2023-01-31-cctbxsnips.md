---
layout: post
title: "CCTBX snippets for text editors"
date: 2023-01-31
permalink: /posts/2023/01/31/cctbxsnips
tags:
  - crystallograhic computing
  - code snippets
  - Python
  - GhostText
  - text editors
  - Vim
  - Emacs
  - VScode
  - Atom
  - Sublime Text
---
The Computational Crystallography Toolbox (cctbx) is a library of functions that support numerical computing in crystallography.
The library is written in C++ for speed. 
It is also wrapped in Python to ease its use.
The Phenix software suite depends on cctbx but not vice vera.
The Olex2 small molecule refinement package also depends on cctbx.
In spite of several excellent tutorials on the cctbx website, many scientists find cctbx hard to penetrate.
I developed a library of snippets to help ease the use of cctbx.
This library was initially made available for use in [Jupyter and Colab](https://github.com/MooersLab/MooersLab/blob/main/README.md#cctbxsnips-for-notebooks), but it is now available at MooersLab on GitHub for the leading [text editors](https://github.com/MooersLab/MooersLab/blob/main/README.md)#cctbxsnips-for-editors): VScode, Vim, NeoVim, Emacs, Sublime Text, and Atom.
These editors can also use GhostText to edit Jupuyter and Colab notebooks and use th cctbxsnip library while doing so.
