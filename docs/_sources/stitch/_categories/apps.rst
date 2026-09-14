Apps
====

Launching MPI applications across a job's allocation with knit run.

.. _stitch-register-an-mpi-app:

Register an MPI app
-------------------

*Declare an app with knit_register_app; its body runs once per MPI rank, and knit records outputs from rank 0 only.*

**APIs:** ``knit_register_app``, ``knit_output``

.. include:: /stitch/recipes/register-an-mpi-app.rst

.. _stitch-read-the-mpi-environment:

Read a rank's place in the MPI world
------------------------------------

*An app body branches on its own rank via the normalized KNIT_MPI_RANK, KNIT_MPI_SIZE, and KNIT_MPI_LOCAL_RANK.*

**APIs:** ``KNIT_MPI_RANK``, ``KNIT_MPI_SIZE``, ``KNIT_MPI_LOCAL_RANK``

.. include:: /stitch/recipes/read-the-mpi-environment.rst

.. _stitch-launch-an-app-from-a-job:

Launch an app from a job
------------------------

*Call knit run --procs N -- <app> from a job body to launch an app across the job's allocation.*

**APIs:** ``run``, ``knit_register_app``, ``knit_job_nodecount``

.. include:: /stitch/recipes/launch-an-app-from-a-job.rst

.. _stitch-control-process-placement:

Control process placement
-------------------------

*Shape how knit run places ranks with --procs, --procs-per-node, --hostnames, and per-rank CPU/GPU binding options.*

**APIs:** ``run``

.. include:: /stitch/recipes/control-process-placement.rst

.. _stitch-pick-a-launcher-backend:

Pick a launcher backend
-----------------------

*Override the launcher knit run uses with --launcher, and pass launcher-native flags with --launcher-args.*

**APIs:** ``run``, ``bootstrap``

.. include:: /stitch/recipes/pick-a-launcher-backend.rst
