****************************************
SalishSeaCast NEMO Model XIOS ARCH Files
****************************************

XIOS build configuration files for the `SalishSeaCast NEMO ocean model`_.

.. _SalishSeaCast NEMO ocean model: http://salishsea-meopar-docs.readthedocs.io/en/latest/index.html


Quick Usage
===========

* If you are a member of the SalishSeaCast organization on GitHub,
  clone the https://github.com/SalishSeaCast/XIOS-2 repository,
  otherwise,
  check out the XIOS source code from the  http://forge.ipsl.jussieu.fr/ioserver/ SVN repository

* Clone this repository beside your XIOS checkout

* Symlink the ``arch-*`` files for the system that you are working on into the
  ``XIOS/arch/`` directory.
  For example, on ``sockeye.arc.ubc.ca``, symlink each of the ``UBC-ARC/arch-GCC_SOCKEYE.*``
  into the ``XIOS/arch/`` directory.

* Build XIOS with ``./make_xios``.
  For example, on ``sockeye``, use ``./make_xios --arch GCC_SOCKEYE --job 8``

Please see the SalishSeaCast NEMO `quick start guide`_ for the system that you are working on
for more details and specific commands.

.. _quick start guide: http://salishsea-meopar-docs.readthedocs.io/en/latest/code-notes/salishsea-nemo/quickstart/index.html#quick-start-guide


License
=======

The SalishSeaCast NEMO Model XIOS ARCH files are copyright 2015 – present by the
`SalishSeaCast Project Contributors`_ and The University of British Columbia.

.. _SalishSeaCast Project Contributors: https://github.com/SalishSeaCast/docs/blob/main/CONTRIBUTORS.rst

They are licensed under the Apache License, Version 2.0.
http://www.apache.org/licenses/LICENSE-2.0
Please see the LICENSE file for details of the license.
