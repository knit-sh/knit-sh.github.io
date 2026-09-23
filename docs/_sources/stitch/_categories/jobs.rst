Jobs
====

Submitting jobs to the scheduler and tracking their lifecycle.

.. _stitch-register-and-submit-a-job:

Register and submit a job
-------------------------

*Register a command as a job and submit it to the scheduler with knit submit.*

**APIs:** ``knit_register_job``, ``submit``, ``knit_with_setup``

.. include:: /stitch/recipes/register-and-submit-a-job.rst

.. _stitch-list-and-submit-job-types:

List the job types you can submit
---------------------------------

*Discover registered jobs with submit --help and submit one with the -- dispatcher syntax.*

**APIs:** ``submit``

.. include:: /stitch/recipes/list-and-submit-job-types.rst

.. _stitch-submit-request-resources:

Request resources for a job
---------------------------

*Ask the scheduler for nodes, walltime, and GPUs with submit --nodes/--walltime/--gpus-per-node.*

**APIs:** ``submit``

.. include:: /stitch/recipes/submit-request-resources.rst

.. _stitch-submit-name-a-job:

Name a job and give it a stable alias
-------------------------------------

*Distinguish submit --name (a knit alias for the job) from --job-name (the scheduler's name).*

**APIs:** ``submit``

.. include:: /stitch/recipes/submit-name-a-job.rst

.. _stitch-submit-account-project-queue:

Set the scheduler account, project, and queue
---------------------------------------------

*Override the accounting and queue for one submission, and set project-wide defaults at bootstrap.*

**APIs:** ``submit``, ``bootstrap``

.. include:: /stitch/recipes/submit-account-project-queue.rst

.. _stitch-job-hosts-and-nodes:

Find the job's hosts and node count
-----------------------------------

*Read a running job's allocated hosts and node count from its body.*

**APIs:** ``knit_job_hostnames``, ``knit_job_nodecount``

.. include:: /stitch/recipes/job-hosts-and-nodes.rst

.. _stitch-job-working-directory:

Write results into the job's directory
--------------------------------------

*Use KNIT_JOB_PREFIX, the job's own working directory, to place output files.*

**APIs:** ``KNIT_JOB_PREFIX``

.. include:: /stitch/recipes/job-working-directory.rst

.. _stitch-wait-for-and-inspect-a-job:

Wait for and inspect a job
--------------------------

*Block on a job, check its lifecycle state, and show its recorded parameters.*

**APIs:** ``submit``, ``job:wait``, ``job:status``, ``job:show``

.. include:: /stitch/recipes/wait-for-and-inspect-a-job.rst

.. _stitch-retrieve-a-job-output:

Retrieve a job's output
-----------------------

*Print a job's captured stdout, stderr, and generated batch script by id.*

**APIs:** ``job:show:stdout``, ``job:show:stderr``, ``job:show:script``

.. include:: /stitch/recipes/retrieve-a-job-output.rst

.. _stitch-cancel-or-resubmit-a-job:

Cancel or resubmit a job
------------------------

*Stop a running job, or replay a past submission as a fresh job.*

**APIs:** ``job:cancel``, ``job:resubmit``

.. include:: /stitch/recipes/cancel-or-resubmit-a-job.rst

.. _stitch-prepare-a-job:

Prepare a job instead of submitting it
--------------------------------------

*Build and record a job without dispatching it, leaving it queued as a prepared row.*

**APIs:** ``prepare``, ``job:cancel``

.. include:: /stitch/recipes/prepare-a-job.rst

.. _stitch-release-prepared-jobs:

Release prepared jobs
---------------------

*Hand prepared jobs to the scheduler one at a time, by id or oldest-first, with a drain loop.*

**APIs:** ``submit:next``, ``submit:prepared``

.. include:: /stitch/recipes/release-prepared-jobs.rst

.. _stitch-drain-prepared-jobs:

Drain a prepared batch with submit drain
----------------------------------------

*Release a whole prepared batch in one command, throttled to N jobs at once.*

**APIs:** ``submit:drain``

.. include:: /stitch/recipes/drain-prepared-jobs.rst

.. _stitch-prepare-from-a-plan:

Prepare many jobs from a plan
-----------------------------

*Prepare a whole batch of jobs from a JSON plan, including a GitHub-Actions-style matrix.*

**APIs:** ``prepare:from``

.. include:: /stitch/recipes/prepare-from-a-plan.rst
