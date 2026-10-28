Parameter search
================

Exploring a declared parameter space: exhaustive sweeps with knit sweep and Bayesian optimization with the knit-ax plugin.

Declare a parameter's search domain
-----------------------------------

*Attach a value set or range to a parameter with --domain for sweeps and optimization.*

**APIs:** ``knit_with_optional``, ``knit_with_required``, ``knit_parameter_space``, ``knit_parameter_space_json``

.. include:: /stitch/recipes/declare-a-search-domain.rst

Run a parameter sweep
---------------------

*Run a command, job, or app once per point in a cartesian product of values with knit sweep.*

**APIs:** ``sweep``, ``submit:drain``, ``knit_with_optional``, ``knit_parameter_space``, ``knit_command_parameters``

.. include:: /stitch/recipes/run-a-parameter-sweep.rst

.. _stitch-optimize-a-job-with-bayesian-search:

Optimize a job with Bayesian search
-----------------------------------

*Tune a job's recorded output with the knit-ax plugin's Bayesian ask/tell loop over a declared search domain.*

**APIs:** ``knit_import``, ``knit_with_optional``, ``knit_with_output``, ``knit_with_table``, ``knit_get_parameter``, ``knit_output``

.. include:: /stitch/recipes/optimize-a-job-with-bayesian-search.rst
