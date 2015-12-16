.. |date| date::

**tldr**: paths and environment variables required to run different
**Leukgen** pipelines.

********************
Leukgen environments
********************

:authors: Gunes Gundem, Komal Rathi, Juan Medina
:contact: medinaj@mskcc.org
:organization: Memorial Sloan-Kettering
:status: This is "work in progress"
:date: |date|

Introduction
============

Common paths and environment variables required to run **Leukgen** pipelines.
To use a desired environment, add it to your bash profile:

.. code:: bash

    # your bash profile
    if [ -f /ifs/work/leukgen/opt/.env/cgp ]; then
       . /ifs/work/leukgen/opt/.env/cgp
    fi

    note: add ``export LKNOINTRO=true`` to your profile to avoid welcome
    message.

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


PATH
====

Tools::

    PATH=$PATH:$LKOPT/R/R-3.2.3/bin                         # R
    PATH=$PATH:$CENTOS6/bedtools/bedtools-2.22.0/bin        # bed tools
    PATH=$PATH:$CENTOS6/samtools/samtools-1.2/htslib-1.2.1  # sam tools
    PATH=$PATH:$CENTOS6/perl/perl-5.20.2_THREAD/bin         # perl

**LSF** executables::

    PATH=$PATH:/common/lsf/9.1/linux2.6-glibc2.3-x86_64/etc
    PATH=$PATH:/common/lsf/9.1/linux2.6-glibc2.3-x86_64/bin

    todo: install pipelines and document the path here


