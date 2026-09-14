Results & artifacts
===================

Marking the headline result of a command and declaring the files it produces as exportable artifacts.

Mark an output as the result
----------------------------

*Flag the output that is what the experiment was for with --result, so knit describe highlights it.*

**APIs:** ``knit_with_output``, ``knit_output``

.. include:: /stitch/recipes/mark-an-output-as-the-result.rst

.. _stitch-declare-and-bind-an-artifact:

Declare and bind an artifact
----------------------------

*Declare a produced file with knit_with_output_artifact, write it under knit_artifact_dir, then bind it with knit_artifact.*

**APIs:** ``knit_with_output_artifact``, ``knit_artifact_dir``, ``knit_artifact``

.. include:: /stitch/recipes/declare-and-bind-an-artifact.rst

.. _stitch-fan-out-a-variadic-output:

Fan out a variadic output
-------------------------

*Declare a *-quantified output artifact and bind the same name many times, so one command produces a whole collection.*

**APIs:** ``knit_with_output_artifact``, ``knit_artifact_dir``, ``knit_artifact``

.. include:: /stitch/recipes/fan-out-a-variadic-output.rst

.. _stitch-link-or-copy-an-artifact:

Link or copy an artifact into place
-----------------------------------

*Create an artifact from a file elsewhere with knit_artifact --copy-from (snapshot) or --link-from (reference in place).*

**APIs:** ``knit_artifact``

.. include:: /stitch/recipes/link-or-copy-an-artifact.rst

Trace an artifact back to its producer
--------------------------------------

*Recover which invocation produced a file by walking the produced edge from its artifacts row back to the producing command.*

**APIs:** ``query:graph``, ``query:sql``, ``knit_with_output_artifact``

.. include:: /stitch/recipes/trace-an-artifact-to-its-producer.rst

Walk an artifact's full lineage
-------------------------------

*Walk producer --produced--> artifact --used_by--> consumer in one query by joining the two provenance edges on the artifact's row.*

**APIs:** ``query:graph``, ``query:sql``, ``knit_with_input_artifact``, ``knit_with_output_artifact``

.. include:: /stitch/recipes/walk-artifact-lineage.rst

.. _stitch-declare-an-artifact-kind:

Declare an artifact kind
------------------------

*Give an artifact a semantic kind with knit_register_artifact, then produce it by naming the kind in knit_with_output_artifact.*

**APIs:** ``knit_register_artifact``, ``knit_with_output_artifact``, ``knit_artifact``

.. include:: /stitch/recipes/declare-an-artifact-kind.rst

.. _stitch-consume-an-input-artifact:

Consume an artifact by kind
---------------------------

*Require a produced artifact of a given kind with knit_with_input_artifact, resolve it with knit_input_artifact_path, and record a used_by edge.*

**APIs:** ``knit_with_input_artifact``, ``knit_input_artifact_path``

.. include:: /stitch/recipes/consume-an-input-artifact.rst

.. _stitch-consume-many-artifacts-with-a-glob:

Consume many artifacts with a glob
----------------------------------

*Declare a +/* input artifact and read every member with knit_input_artifact_paths, passing a comma list or a glob.*

**APIs:** ``knit_with_input_artifact``, ``knit_input_artifact_paths``

.. include:: /stitch/recipes/consume-many-artifacts-with-a-glob.rst

.. _stitch-discover-and-merge-artifacts:

Discover and merge a fan-out
----------------------------

*Pair a *-output producer with a +/* -input consumer so one command scatters many artifacts and the next gathers them by glob.*

**APIs:** ``knit_with_output_artifact``, ``knit_artifact``, ``knit_with_input_artifact``, ``knit_input_artifact_paths``

.. include:: /stitch/recipes/discover-and-merge-artifacts.rst
