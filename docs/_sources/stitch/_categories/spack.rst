Spack
=====

Working with Spack environments and package specs.

.. _stitch-pin-spack-specs:

Pin a setup's Spack specs
-------------------------

*List the Spack packages a setup needs and let knit build them.*

**APIs:** ``knit_with_spack_specs``, ``knit_register_setup``, ``KNIT_SETUP_PREFIX``

.. include:: /stitch/recipes/pin-spack-specs.rst

.. _stitch-use-spack-manifest:

Use a full Spack manifest
-------------------------

*Describe a setup's Spack environment with a complete spack.yaml.*

**APIs:** ``knit_with_spack_env``, ``knit_register_setup``

.. include:: /stitch/recipes/use-spack-manifest.rst

Build an MPI environment and provide a launcher
-----------------------------------------------

*Ask Spack for an MPI provider in a setup and expose it as the run launcher.*

**APIs:** ``knit_register_setup``, ``knit_with_spack_specs``, ``knit_provides_launcher``

.. include:: /stitch/recipes/mpi-setup-launcher.rst

.. _stitch-run-spack-directly:

Run Spack directly
------------------

*Drive the experiment's private Spack with the knit spack wrapper.*

**APIs:** ``spack``, ``bootstrap``

.. include:: /stitch/recipes/run-spack-directly.rst

.. _stitch-isolate-spack-config:

Isolate Spack from your personal config
---------------------------------------

*Knit's Spack ignores ~/.spack and site config so the environment stays reproducible.*

**APIs:** ``spack``

.. include:: /stitch/recipes/isolate-spack-config.rst

Pin the Spack version
---------------------

*Provision a specific Spack (and package repo) git ref at bootstrap.*

**APIs:** ``bootstrap``

.. include:: /stitch/recipes/bootstrap-pin-spack.rst
