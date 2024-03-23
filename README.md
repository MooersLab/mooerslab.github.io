![Version](https://img.shields.io/static/v1?label=mooerslab.github.io&message=0.3&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

# Repository for the Mooers Lab GitHub Page

The webpage is accessed via [this link](https://mooerslab.github.io).
This webpage includes a blog post.
This is still a work in progress.

## Source of the webpage template
The code for this site was adapted from a Github Pages template for academic websites by [Stuart Geiger](https://github.com/staeiou).
He forked (then detached) by from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License. 
See LICENSE.md.

## Notes for editing

The *_config.yaml* file controls the appearance of the webpage. 
The about.md file in the *_pages* directory contains the content of the main webpage. 
The *_pages* is to contain PDFs of papers. The *_talks* is to contain PDFs of talks. 
The blog posts are in *_posts*. 
They must be written in markdown. 
The filenames of the blog post files following a specified format.
Many of the files require some yaml code at the top of the file or else they will not be read by Jekyll and converted into a html file correctly.
There is a Guide to the markdown and other details of this webpage template under the Guide pull-down.

### Notes on editing the blog post files

The blog posts are in separate markdown files.
These files have to strictly adhere to the file format:

- The file name in the in the yaml header of the file has whitespaces replaced with forward slashes. These slashes are replaced with dashes in the filename.
- The file name has to start with the date.
- The file extension has to be *.md*.

The post will appear several minutes after the file is commited. The post will not appear if there is a problem with the format or filename.
