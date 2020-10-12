# fastdoc
> Create publication-quality books from Jupyter notebooks


The output of `fastdoc` is an [asciidoc](https://asciidoc.org/) file for each input notebook. You can then use [asciidoctor](https://asciidoctor.org/) to convert that to HTML, DocBook, epub, mobi, and so forth.

## Install

`pip install fastdoc` or `conda install fastdoc`

## How to use

Create notebooks in a folder called `book`. From that folder, run `fastdoc_convert_all` in your terminal. You'll find your exported asciidoc files and all images used in `../convert_book`. For a single notebook demonstrating all the features of `fastdoc`, see the `test/_test.ipynb` notebook. For a complete O'Reilly book written in this way, see [fastbook](https://github.com/fastai/fastbook/).

