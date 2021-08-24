# CCBL's jupyter book

## Install and build jupyter book

To build modifications on this book, one needs

* First, install `jupyter-book`:

```
pip install -U jupyter-book
```

* Then, build: 

```
jupyter-book build collaborative_benchmarking
```

The file `_build/html/index.html` shows a preview of the book.

The full documentation is [here](https://jupyterbook.org/intro.html).

## Publish your book online with GitHub Pages

The book is published from main directory.

* First, install `ghp-import`:

```
pip install ghp-import
```

* Then, call `ghp-import`:

```
ghp-import -n -p -f _build/html
```

The book should be accessible at [collaborative_benchmarking](https://computational-chemical-biology.github.io/collaborative_benchmarking).
