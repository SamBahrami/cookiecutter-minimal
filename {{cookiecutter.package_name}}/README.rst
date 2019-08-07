{{ cookiecutter.package_name|count * "=" }}
{{ cookiecutter.package_name }}
{{ cookiecutter.package_name|count * "=" }}

{{ cookiecutter.package_description }}

Usage
=====

Installation
------------
.. code-block:: bash

  $ conda env create --file environment.yaml
  $ conda activate {{cookiecutter.package_name}}

Tests
-----
.. code-block:: bash

  $ pytest tests

Command Line Interface
----------------------
.. code-block:: bash

  $ {{cookiecutter.package_name}} --help

Authors
-------

`{{ cookiecutter.package_name }}` was written by `{{ cookiecutter.author_name }} <{{ cookiecutter.author_email }}>`_.
