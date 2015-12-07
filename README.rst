.. |date| date::

**abstract**: Paths and environment variables required to run different
**Leukgen** pipelines.

********************
Leukgen environments
********************

:authors: Gunes Gundem, Komal Rathi, Juan Medina
:contact: medinaj@mskcc.org
:organization: Memorial Sloan-Kettering
:status: This is "work in progress"
:date: |date|
:license: BSD

Description
-----------

Commonly paths and environment variables required to run different
**Leukgen** pipelines are stored in ``/ifs/work/leukgen/opt/.env``.

To use a desired environment, add it to your bash profile:

.. code:: bash

    # your bash profile
    if [ -f /ifs/work/leukgen/opt/.env/cgp ]; then
       . /ifs/work/leukgen/opt/.env/cgp
    fi
