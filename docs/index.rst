:tocdepth: 2

=================================================
svviz - a read visualizer for structural variants
=================================================


.. toctree::
   :maxdepth: 1

   self
   intro
   features
   install
   webinterface
   commandline
   faqs
   changelog
   license


svviz visualizes high-throughput sequencing data that supports a structural variant. svviz is free and open source, available at `<https://github.com/svviz/svviz>`_. Please submit issues, questions or feature requests using the `github issue tracker <https://github.com/svviz/svviz/issues>`_.

Visit the `project page <http://svviz.github.io/svviz/>`_ for a visual tour of the features, or continue through this documentation for more detailed information about svviz.

.. image:: example.png
    :width: 95%
    :align: center

|
|


News
----

**Sept, 2015 -- Publication** The final version of the svviz paper is now `available in Bioinformatics <http://dx.doi.org/10.1093/bioinformatics/btv478>`_.

**July, 2015 -- Multimapping** new capabilities have been added to identify repetitiveness near the structural variant and to more aggressively filter out reads that could potentially align to multiple locations. See :ref:`here <dotplots>` for more information. With the default settings, svviz should recover more alt- and ref-supporting reads while filtering more truly ambiguous reads.


Quick-start
-----------

1. Install the latest version of svviz from github: ``sudo pip install svviz``
2. Run the following command: ``svviz demo``

Detailed instructions, including how to ensure that all prerequisites are installed, are available on the :ref:`installation` page.

Citation
--------

svviz has been `published in Bioinformatics <http://dx.doi.org/10.1093/bioinformatics/btv478>`_. If you found svviz useful for your research, please cite svviz as follows:

Spies N, Zook JM, Salit M, Sidow A. 2015. svviz: a read viewer for validating structural variants. Bioinformatics doi:bioinformatics/btv478.

svviz was developed by `Noah Spies <http://stanford.edu/~nspies/>`_, a member of the `Sidow lab <http://mendel.stanford.edu/SidowLab/index.html>`_ at Stanford and part of the `Joint Initiative for Metrology in Biology (JIMB) <http://jimb.stanford.edu/>`_. Funding was provided by the `National Institute of Standards and Technology (NIST) <http://www.nist.gov>`_.