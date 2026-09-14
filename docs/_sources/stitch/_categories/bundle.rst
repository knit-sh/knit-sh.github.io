Bundle & export
===============

Packing an experiment into one shippable archive with knit bundle, and exporting a standard RO-Crate manifest of its provenance.

.. _stitch-make-a-shippable-bundle:

Make a shippable bundle
-----------------------

*Pack the whole experiment into one relocatable archive with knit bundle, ready to send to a collaborator or deposit in a repository.*

**APIs:** ``bundle``

.. include:: /stitch/recipes/make-a-shippable-bundle.rst

.. _stitch-declare-extra-bundle-files:

Declare extra files to bundle
-----------------------------

*List side files Knit does not track — a config, an input, a plotting script, or a whole glob — with knit_bundle_requires so knit bundle carries them.*

**APIs:** ``knit_bundle_requires``

.. include:: /stitch/recipes/declare-extra-bundle-files.rst

.. _stitch-export-an-ro-crate-manifest:

Export an RO-Crate manifest
---------------------------

*Describe the experiment's provenance as a standard RO-Crate / Process Run Crate manifest, embedded in a bundle with --ro-crate or emitted alone with knit export ro-crate.*

**APIs:** ``bundle``, ``export:ro-crate``

.. include:: /stitch/recipes/export-an-ro-crate-manifest.rst
