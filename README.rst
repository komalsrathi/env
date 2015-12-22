.. |date| date::

**tldr**: Leukgen environments and aliases.

********************
Leukgen environments
********************

:authors: Gunes Gundem, Komal Rathi, Juan Medina
:contact: medinaj@mskcc.org
:organization: Memorial Sloan-Kettering
:status: This is "work in progress"
:date: |date|

.. meta::
   :keywords: environments, leukgen, path
   :description lang=en: Leukgen environments and aliases.

Introduction
============

Common environments required to run **Leukgen** pipelines are stored here.
To use a desired environment, add it to your bash profile:

.. code:: bash

    # your bash profile
    if [ -f /ifs/work/leukgen/opt/.env/cgp ]; then
       . /ifs/work/leukgen/.env/cgp
    fi

.. note::
    Add ``export LKNOINTRO=true`` to your profile to avoid welcome message.


Environments
============

* :doc:`cgp`

Aliases
=======

* :doc:`gitaliases`


