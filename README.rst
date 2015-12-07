.. |date| date::

********************
Leukgen environments
********************

:author: Gunes Gundem, Komal Rathi, Juan Medina
:contact: medinaj@mskcc.org
:organization: Memorial Sloan-Kettering
:status: This is "work in progress"
:date: |date|

Paths and environment variables required to run different **Leukgen**
pipelines.

LICENSE: BSD

Usage
-----

Add the desired environment to you bash profile, for instance:

.. code:: bash

    # load cgp environment
    if [ -f /ifs/work/leukgen/opt/.env/cgp ]; then
       . /ifs/work/leukgen/opt/.env/cgp
    fi
