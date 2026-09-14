Types
=====

Annotating parameters with types and defining enums.

.. _stitch-type-annotate-parameter:

Type-annotate a parameter
-------------------------

*Give a parameter a type so knit validates its value automatically.*

**APIs:** ``knit_with_required``, ``knit_with_optional``, ``knit_type_check``

.. include:: /stitch/recipes/type-annotate-parameter.rst

.. _stitch-define-and-use-enum:

Define and use an enum
----------------------

*Restrict a parameter to a fixed set of values with a custom enum type.*

**APIs:** ``knit_enum``, ``knit_enum_values``, ``knit_with_required``

.. include:: /stitch/recipes/define-and-use-enum.rst

.. _stitch-checksum-a-file-parameter:

Checksum a file or directory parameter
--------------------------------------

*Record the path and a sha256 content checksum of a file/directory input or output, and opt out with --no-checksum.*

**APIs:** ``knit_with_required``, ``knit_with_optional``, ``knit_with_output``, ``knit_output``, ``knit_with_table``

.. include:: /stitch/recipes/checksum-a-file-parameter.rst

How knit types map to SQL columns
---------------------------------

*A recorded column's SQL affinity follows its knit type --- integer to INTEGER, real to REAL, everything else to TEXT.*

**APIs:** ``knit_with_table``, ``knit_with_output``

.. include:: /stitch/recipes/knit-types-to-sql-columns.rst
