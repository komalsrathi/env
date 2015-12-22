.. |date| date::

**tldr**: **CGP** environment documentation.

***********************
leukgen CGP environment
***********************

:authors: Gunes Gundem, Komal Rathi, Juan Medina
:contact: rathik@mskcc.org, medinaj@mskcc.org
:organization: Memorial Sloan-Kettering
:status: This is "work in progress"
:date: |date|

.. meta::
   :keywords: environments, CGP, leukgen, path
   :description lang=en: CGP environment documentation.

Introduction
============

Add to your bash profile:

.. code:: bash

    if [ -f /ifs/work/leukgen/opt/.env/cgp ]; then
       . /ifs/work/leukgen/.env/cgp
    fi

Variables
=========

The following environment variables are available to **leukgen** users:

.. code:: bash

    LK=/ifs/work/leukgen
    LKOPT=/ifs/work/leukgen/opt
    LKREF=/ifs/work/leukgen/REF
    LKLIB=/ifs/work/leukgen/lib
    LKUSERS=/ifs/work/leukgen/users
    LKWORKFLOWS=/ifs/work/leukgen/workflows
