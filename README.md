# cloud-docs [![Documentation Status](https://readthedocs.org/projects/incendocloud/badge/?version=latest)](https://cloud.incendo.org/en/latest/?badge=latest)

Documentation for Cloud v2.
The docs are written in markdown using [MkDocs](https://www.mkdocs.org/).
The docs are automatically built & deployed when pushing to the `main` branch and the docs are available on [cloud.incendo.org](https://cloud.incendo.org).
Each PR will deploy a temporary preview version of the site.

## Install & Build

You can install MkDocs by using
```shell
$ python3 -m pip install -r docs/requirements.txt
```
and then you may run MkDocs locally using
```shell
$ mkdocs serve
```
after which the docs will be available at `http://127.0.0.1:8000/`.
The built site will auto-refresh when the files are updated.