# Introduction

A [`copier`](https://copier.readthedocs.io/en/latest/)-based template for Python packages related to the MC3D project.

## Design decisions

Every MC3D repository should be:

1. `pip`-installable, so it can host Python code which can be used in scripts etc.
1. able to host the "pipeline" for generating the data.
1. able to document the project easily.

### Layout and packaging

The Python package for each MC3D repository follows the modern [`src` layout](https://packaging.python.org/en/latest/discussions/src-layout-vs-flat-layout/
) and we use [`hatch`](https://hatch.pypa.io/) for the build system and several other project management tools.

### Documentation

We choose [MkDocs](https://www.mkdocs.org/) as the preffered framework for documenting the project:

1. Markdown-based
1. Simple to build and write
1. Static pages, easy to host
1. Sexy AF with [Material for MkDocs](https://github.com/squidfunk/mkdocs-material)
