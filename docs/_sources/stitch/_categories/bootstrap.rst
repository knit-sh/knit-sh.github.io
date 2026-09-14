Bootstrap
=========

Initializing an experiment with knit bootstrap.

.. _stitch-bootstrap-an-experiment:

Bootstrap an experiment
-----------------------

*Initialize an experiment's .knit/ directory before running any command.*

**APIs:** ``bootstrap``

.. include:: /stitch/recipes/bootstrap-an-experiment.rst

.. _stitch-bootstrap-project-and-account:

Set the scheduler project and account
-------------------------------------

*Record the batch-scheduler project and account jobs are submitted under.*

**APIs:** ``bootstrap``

.. include:: /stitch/recipes/bootstrap-project-and-account.rst

.. _stitch-bootstrap-setup-and-job-paths:

Choose where setups and jobs live
---------------------------------

*Point the setup and job root directories at custom locations.*

**APIs:** ``bootstrap``

.. include:: /stitch/recipes/bootstrap-setup-and-job-paths.rst

.. _stitch-bootstrap-select-scheduler:

Select the batch scheduler
--------------------------

*Pin the batch scheduler instead of auto-detecting it.*

**APIs:** ``bootstrap``

.. include:: /stitch/recipes/bootstrap-select-scheduler.rst

.. _stitch-bootstrap-select-launcher:

Select the MPI launcher
-----------------------

*Pin the MPI launcher instead of auto-detecting it.*

**APIs:** ``bootstrap``, ``knit_provides_launcher``

.. include:: /stitch/recipes/bootstrap-select-launcher.rst

.. _stitch-bootstrap-job-defaults:

Set project-wide job defaults
-----------------------------

*Freeze default walltime and per-node core count for submitted jobs.*

**APIs:** ``bootstrap``

.. include:: /stitch/recipes/bootstrap-job-defaults.rst

.. _stitch-bootstrap-pin-spack:

Pin the Spack version
---------------------

*Provision a specific Spack (and package repo) git ref at bootstrap.*

**APIs:** ``bootstrap``

.. include:: /stitch/recipes/bootstrap-pin-spack.rst

.. _stitch-bootstrap-bundled-tools:

Force building the bundled tools from source
--------------------------------------------

*Build sqlite/jq from source instead of symlinking the system copies.*

**APIs:** ``bootstrap``

.. include:: /stitch/recipes/bootstrap-bundled-tools.rst

.. _stitch-bootstrap-pin-cypher-to-sql:

Pin the knit-cypher-to-sql version
----------------------------------

*Provision a specific knit-cypher-to-sql release, or one from a custom URL.*

**APIs:** ``bootstrap``

.. include:: /stitch/recipes/bootstrap-pin-cypher-to-sql.rst

.. _stitch-bootstrap-update-configuration:

Update configuration by re-running bootstrap
--------------------------------------------

*Re-run bootstrap to change settings in place without losing the database or runs.*

**APIs:** ``bootstrap``

.. include:: /stitch/recipes/bootstrap-update-configuration.rst
