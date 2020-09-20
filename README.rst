|logo|

*One-line description here!*

|website| |release| |rtd| |license|

My Python Library
=================

This is a template for creating new python library. Here are some descriptions!

Here are some features

* print Hello World
* print many Hello Worlds!

**Documentation**: https://mypthonlibrary.readthedocs.io

**Repository**: https://github.com/terrencetec/mypythonlibrary

.. contents::
   :depth: 2

Getting Started
===============

Dependencies
------------

Required
^^^^^^^^
* Package 1
* Package 2
* Package 3

pip:

In principle, if you are using `pip`, you don't have to install dependencies
beforehand. When you install this package, `pip` will 
.. code:: bash

   pip install package1 package2 package3

If you use conda:

.. code:: bash

   conda install -c conda-forge package1 package2 package3

Optional
^^^^^^^^
* Package 4

pip:

.. code:: bash

   pip install package4

Conda:

.. code:: bash

   conda install -c conda-forge package4

Install from source
-------------------

.. code:: bash

   git clone https://github.com/terrencetec/mypythonlibrary.git
   cd mypythonlibrary
   pip install .

For Developers
==============

Standards and Tools
-------------------
Please comply with the following standards/guides as much as possible.

Coding style
^^^^^^^^^^^^
- **PEP 8**: https://www.python.org/dev/peps/pep-0008/

CHANGELOG
^^^^^^^^^
- **Keep a Changelog**: https://keepachangelog.com/en/1.0.0/

Versioning
^^^^^^^^^^
- **Semantic Versioning**: https://semver.org/spec/v2.0.0.html

Packaging
^^^^^^^^^
- **PyPA**: https://www.pypa.io
- **python-packaging**: https://python-packaging.readthedocs.io

Documentation
^^^^^^^^^^^^^
- **NumPy docstrings**: https://numpydoc.readthedocs.io/en/latest/format.html
- **Sphinx**: https://www.sphinx-doc.org/
- **Read The Docs**: https://readthedocs.org/
- **Documenting Python Code: A Complete Guide**: https://realpython.com/documenting-python-code/

How to Contribute
-----------------

Use the code and file an issue!

Cheat sheet
-----------

Sphinx
^^^^^^

Generate documentation base, in docs/,

.. code:: bash

   sphinx-quickstart

Select separate build and source files when prompted.

Preview documentation page with modified source, in docs/

.. code:: bash

   make html

Open index.html with a browser (if this was set as the first page).

.. |logo| image:: logo.svg
    :alt: Logo
    :target: https://github.com/terrencetec/mypythonlibrary

.. |website| image:: https://img.shields.io/badge/website-mypythonlibrary-blue.svg
    :alt: Website
    :target: https://github.com/terrencetec/mypythonlibrary

.. |release| image:: https://img.shields.io/github/v/release/terrencetec/mypythonlibrary?include_prereleases
   :alt: Release
   :target: https://github.com/terrencetec/mypythonlibrary/releases

.. |rtd| image:: https://readthedocs.org/projects/mypythonlibrary/badge/?version=latest
   :alt: Read the Docs
   :target: https://mypythonlibrary.readthedocs.io/

.. |license| image:: https://img.shields.io/github/license/terrencetec/mypythonlibrary
    :alt: License
    :target: https://github.com/terrencetec/mypythonlibrary/blob/master/LICENSE
