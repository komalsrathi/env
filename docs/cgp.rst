.. |date| date::

**tldr**: environment required to run the cgp pipelines.

***********************
leukgen cgp environment
***********************

:authors: Gunes Gundem, Komal Rathi, Juan Medina
:contact: rathik@mskcc.org, medinaj@mskcc.org
:organization: Memorial Sloan-Kettering
:status: This is "work in progress"
:date: |date|


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


cgpVcf
======

version **1.2.3** installed at ``$LKOPT/cgpVcf/1.2.3``

**dependencies** installed:

* `vcftools`_ **0.1.14** installed at ``$LKOPT/vcftools/0.1.14``.
* `htslib`_ **1.3** installed at ``$LKOPT/htslib/1.3``.

Perl libraries installed:

* `DataUUID`_ **1.221**.

.. references:

.. _vcftools: https://github.com/vcftools/vcftools
.. _htslib: https://github.com/samtools/htslib
.. _DataUUID: http://search.cpan.org/dist/Data-UUID/UUID.pm
