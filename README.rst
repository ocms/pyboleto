========
pyboleto
========

**pyboleto-quicksys** is a Python library to generate Brazilian bank payment slips (boletos de cobrança bancária).

This project is based on the original pyboleto library by Eduardo Cereto Carvalho and includes updates and maintenance by Orlando Cesar Martins.

Features
========

* Generate Brazilian bank payment slips.
* Support for multiple Brazilian banks.
* PDF generation using ReportLab.
* Updated boleto due date factor according to the FEBRABAN rule introduced in February 2025.

Implemented Banks
=================

The original project includes implementations for:

* Banco do Brasil
* Banrisul
* Bradesco
* Caixa Econômica Federal
* HSBC
* Itaú
* Real
* Santander

Installation
============

Install using pip::

    pip install pyboleto-quicksys

Usage
=====

The Python module retains its original name::

    import pyboleto

Examples
========

See the examples in the ``bin`` directory:

* ``pdf_pyboleto_sample.py``
* ``html_pyboleto_sample.py``

Development
===========

The source code is available at:

https://github.com/ocms/pyboleto

License
=======

This project retains the original New BSD License.

See the LICENSE file for details.

Credits
=======

Original project:

https://github.com/eduardocereto/pyboleto

Original author: Eduardo Cereto Carvalho

Maintained and updated by Orlando Cesar Martins.