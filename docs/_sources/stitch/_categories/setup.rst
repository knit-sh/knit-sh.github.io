Setup
=====

Defining and provisioning software environments.

.. _stitch-register-a-setup:

Register a setup
----------------

*Register a setup that builds and installs software into its own prefix.*

**APIs:** ``knit_register_setup``, ``knit_with_spack_specs``, ``KNIT_SETUP_PREFIX``

.. include:: /stitch/recipes/register-a-setup.rst

.. _stitch-keep-setups-thin:

Keep setup functions thin
-------------------------

*Delegate dependency installation to a package manager and keep the setup body minimal.*

**APIs:** ``knit_with_spack_specs``, ``knit_with_spack_env``, ``knit_setup_env_set``

.. include:: /stitch/recipes/keep-setups-thin.rst

Make a spec depend on a parameter
---------------------------------

*Reference a setup parameter from a spec or manifest with a {{placeholder}}.*

**APIs:** ``knit_with_spack_specs``, ``knit_with_spack_env``, ``knit_with_uv_specs``, ``knit_with_required``, ``knit_with_optional``

.. include:: /stitch/recipes/parameterize-a-spec.rst

Generate specs or a manifest with a function
--------------------------------------------

*Let a function produce a setup's specs (or whole manifest) at invocation time.*

**APIs:** ``knit_with_spack_specs_from``, ``knit_with_spack_env_from``, ``knit_with_uv_specs_from``, ``knit_with_uv_env_from``, ``knit_get_parameter``, ``knit_with_flag``, ``knit_with_required``

.. include:: /stitch/recipes/generate-specs-with-a-function.rst

.. _stitch-declare-a-setup-environment:

Declare a setup's environment
-----------------------------

*Declare environment changes a setup passes to dependent commands, composably.*

**APIs:** ``knit_setup_env_set``, ``knit_setup_env_prepend``, ``knit_setup_env_append``, ``knit_setup_env_unset``, ``knit_setup_activate_line``

.. include:: /stitch/recipes/declare-a-setup-environment.rst

.. _stitch-depend-on-a-setup:

Depend on a setup
-----------------

*Bind a command to a setup so it runs inside that software environment.*

**APIs:** ``knit_with_setup``

.. include:: /stitch/recipes/depend-on-a-setup.rst

.. _stitch-mpi-setup-launcher:

Build an MPI environment and provide a launcher
-----------------------------------------------

*Ask Spack for an MPI provider in a setup and expose it as the run launcher.*

**APIs:** ``knit_register_setup``, ``knit_with_spack_specs``, ``knit_provides_launcher``

.. include:: /stitch/recipes/mpi-setup-launcher.rst

.. _stitch-provide-default-setup:

Provide the default setup
-------------------------

*Understand the builtin default setup that jobs adopt, and how to opt out.*

**APIs:** ``knit_without_setup``, ``knit_with_setup``, ``knit_register_job``

.. include:: /stitch/recipes/provide-default-setup.rst
