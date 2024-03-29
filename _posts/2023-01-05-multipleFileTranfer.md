---
layout: post
title: "Script for easier multiple file transfer posted on GitHub"
date: 2023-01-05
permalink: /posts/2023/01/05/multipleFileTransfer
tags:
  - multiple file transfer
  - scp
  - sshpass
  - remote computers
  - clusters
  - supercomputing
  - OSCER at OU
---
One annoying and time-consuming task in scientific computing and data science is the transfer of multiple large tar archive files of raw data files from remote computers to local ones. We do this task frequently in our structural biology work. I assembled a [bash script](https://github.com/MooersLab/multipleFileTransfer) that eases this chore. You can use the script to pass your password. This script negates the need to enter your password before each tar file is transferred. The script notifies you audibly when it finishes.
