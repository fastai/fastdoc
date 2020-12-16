
# fastdoc
> Create publication-quality books from Jupyter notebooks


The output of `fastdoc` is an [asciidoc](https://asciidoc.org/) file for each input notebook. You can then use [asciidoctor](https://asciidoctor.org/) to convert that to HTML, DocBook, epub, mobi, and so forth.

## Install

To install using pip:

```bash
pip install fastdoc
```

To install using Conda:

```bash
conda install -c fastai fastdoc
```

## How to use

Suppose your notebook is in a folder called `book`. To run fastdoc:

`fastdoc_convert_all --path book --dest_path convert_book` 

You'll find your exported asciidoc files and all images used in `convert_book`. 

For a single notebook demonstrating all the features of `fastdoc`, see the `test/_test.ipynb` notebook. 

For a complete O'Reilly book written in this way, see [fastbook](https://github.com/fastai/fastbook/).
