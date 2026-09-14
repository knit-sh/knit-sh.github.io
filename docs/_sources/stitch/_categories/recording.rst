Recording
=========

Recording command invocations, their parameters, and their outputs in per-command tables.

.. _stitch-record-invocations-in-a-table:

Record invocations in a table
-----------------------------

*Declare a table with knit_with_table so knit records one row per invocation, with a column per parameter and output.*

**APIs:** ``knit_with_table``

.. include:: /stitch/recipes/record-invocations-in-a-table.rst

.. _stitch-emit-outputs-from-a-command:

Emit outputs from a command
---------------------------

*Declare a result column with knit_with_output and set it from the body with knit_output.*

**APIs:** ``knit_with_output``, ``knit_output``

.. include:: /stitch/recipes/emit-outputs-from-a-command.rst

Checksum a file or directory parameter
--------------------------------------

*Record the path and a sha256 content checksum of a file/directory input or output, and opt out with --no-checksum.*

**APIs:** ``knit_with_required``, ``knit_with_optional``, ``knit_with_output``, ``knit_output``, ``knit_with_table``

.. include:: /stitch/recipes/checksum-a-file-parameter.rst

.. _stitch-knit-types-to-sql-columns:

How knit types map to SQL columns
---------------------------------

*A recorded column's SQL affinity follows its knit type --- integer to INTEGER, real to REAL, everything else to TEXT.*

**APIs:** ``knit_with_table``, ``knit_with_output``

.. include:: /stitch/recipes/knit-types-to-sql-columns.rst

.. _stitch-mark-an-output-as-the-result:

Mark an output as the result
----------------------------

*Flag the output that is what the experiment was for with --result, so knit describe highlights it.*

**APIs:** ``knit_with_output``, ``knit_output``

.. include:: /stitch/recipes/mark-an-output-as-the-result.rst
