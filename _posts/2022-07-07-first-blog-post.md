---
layout: post
title: "MooersLab launches blog in GitHub Pages"
date: 2022-07-07
---

I finally added a blog post to the MooersLab GitHub Pages. 
I am able to edit this file directly in Emacs by using atomic-chrome.el package and the GhostText Extension for Chrome.
(I can do likewise with Neovim, Sublime Text, Visual Studio Code, or Atom with the appropriate plugin for each of these editors.) 
The text that I type in Emacs appears instantly in GitHub.

I have configured atomic-chrome to open the file in Emacs in ghm-mode: GitHub markdown mode.
I do not have to save my edits in Emacs, but I do have to commit the changes on GitHub.
The name of the Emacs buffer is the name of the file on GitHub.
The commit action closes the connection to Emacs and the text in Emacs is lost.
This means that you have commit when you are done with a significant chunk of work.

