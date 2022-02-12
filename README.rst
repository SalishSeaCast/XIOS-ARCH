*************************************
Salish Sea NEMO Model XIOS ARCH Files
*************************************

XIOS build configuration files for the `Salish Sea NEMO ocean model`_.

.. _Salish Sea NEMO ocean model: http://salishsea-meopar-docs.readthedocs.io/en/latest/index.html


Quick Usage
===========

* Check out XIOS source code from the  ``http://forge.ipsl.jussieu.fr/ioserver/`` SVN repository

* Clone this repository beside your XIOS checkout

* Symlink the ``arch-*`` files for the system that you are working on into the
  ``XIOS/arch/`` directory.
  For example, on ``orcinus.westgrid.ca``, symlink each of the ``WESTGRID/arch-X64_ORCINUS.*``
  into the ``XIOS/arch/`` directory.

* Build XIOS with ``./make_xios``.
  For example, on ``orcinus``, use ``./make_xios --arch X64_ORCINUS --job 8``

Please see the Salish Sea NEMO `quick start guide`_ for the system that you are working on
for more details and specific commands.

.. _quick start guide: http://salishsea-meopar-docs.readthedocs.io/en/latest/code-notes/salishsea-nemo/quickstart/index.html#quick-start-guide


License
=======

The Salish Sea NEMO Model XIOS ARCH files are copyright 2015 – prsent by the
`Salish Sea MEOPAR Project Contributors`_ and The University of British Columbia.

.. _Salish Sea MEOPAR Project Contributors: https://github.com/SalishSeaCast/docs/blob/main/CONTRIBUTORS.rst

They are licensed under the Apache License, Version 2.0.
http://www.apache.org/licenses/LICENSE-2.0
Please see the LICENSE file for details of the license.
