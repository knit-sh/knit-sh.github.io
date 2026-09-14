Provenance
==========

Linking recorded rows across tables through the __provenance__ graph of call and used_by edges.

.. _stitch-call-and-used-by-edges:

Understand call and used_by edges
---------------------------------

*The __provenance__ table links recorded rows with directed call and used_by edges, so a query can trace what produced what.*

**APIs:** ``knit_with_setup``

.. include:: /stitch/recipes/call-and-used-by-edges.rst

.. _stitch-opt-in-out-of-provenance:

Opt in/out of the provenance graph
----------------------------------

*Force a command in or out of the provenance graph with knit_with_provenance and knit_without_provenance.*

**APIs:** ``knit_with_provenance``, ``knit_without_provenance``

.. include:: /stitch/recipes/opt-in-out-of-provenance.rst

.. _stitch-distinguish-repeated-calls:

Distinguish repeated calls
--------------------------

*Name a call with knit_as so repeated invocations of the same command can be told apart in a provenance query.*

**APIs:** ``knit_as``

.. include:: /stitch/recipes/distinguish-repeated-calls.rst

Consume an artifact by kind
---------------------------

*Require a produced artifact of a given kind with knit_with_input_artifact, resolve it with knit_input_artifact_path, and record a used_by edge.*

**APIs:** ``knit_with_input_artifact``, ``knit_input_artifact_path``

.. include:: /stitch/recipes/consume-an-input-artifact.rst

Discover and merge a fan-out
----------------------------

*Pair a *-output producer with a +/* -input consumer so one command scatters many artifacts and the next gathers them by glob.*

**APIs:** ``knit_with_output_artifact``, ``knit_artifact``, ``knit_with_input_artifact``, ``knit_input_artifact_paths``

.. include:: /stitch/recipes/discover-and-merge-artifacts.rst
