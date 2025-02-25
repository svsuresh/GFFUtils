GFFUtils
========

Date: Feb25,2025
--------
- GFFutil.py changed so that gtf_extract function works. No other functions are tested
- Installation instructions are exactly identical as documented at http://gffutils.readthedocs.org/
- All the licensing rights on this fork belong to original author except the code changes made.
- Changed files are provided as such and use it at your risk
- Source information is avaiable at: http://gffutils.readthedocs.org
- gff_extract works with python 3.13 (installed from brew), MacOS 13.5


Utilities for working with GFF and GTF files:

* ``gff_cleaner.py``: perform various "cleaning" manipulations on a GFF file
* ``gff_annotation_extractor``: combine and annotate feature counts with data from a GFF or GTF file
* ``gft_extract``: extract selected data items from a GTF file
* ``gtf2bed``: convert GTF contents to BED format

Full documentation is available at http://gffutils.readthedocs.org/

To install the developmental code directly from GitHub:

::

   pip install -r https://raw.githubusercontent.com/fls-bioinformatics-core/GFFUtils/devel/requirements.txt
   pip install git+https://github.com/fls-bioinformatics-core/GFFUtils.git@devel


Licensing
---------

This software is licensed under the Academic Free License 3.

Credits
-------

These utilities have been developed by Peter Briggs with input from Leo Zeef, to support the activities of the Bioinformatics Core Facility
(BCF) in the Faculty of Biology Medicine and Health (FBMH) at the University of Manchester (UoM).
