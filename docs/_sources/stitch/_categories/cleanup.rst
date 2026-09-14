Cleanup
=======

Erasing recorded entities and their provenance with knit remove, from a single row to a whole lineage.

.. _stitch-remove-an-entity-and-its-dependents:

Remove an entity and its dependents
-----------------------------------

*Erase a setup, resource, job, run, or command by name, type, or id, cascading down the provenance graph to everything that used it.*

**APIs:** ``remove:setup``, ``remove:resource``, ``remove:job``, ``remove:run``, ``remove:command``, ``remove:artifact``

.. include:: /stitch/recipes/remove-an-entity-and-its-dependents.rst

.. _stitch-preview-a-removal-with-dry-run:

Preview a removal with --dry-run
--------------------------------

*Print the exact rows, edges, and files a remove would erase without deleting anything or prompting.*

**APIs:** ``remove:setup``, ``remove:job``

.. include:: /stitch/recipes/preview-a-removal-with-dry-run.rst

.. _stitch-erase-a-whole-lineage-with-from-root:

Erase a whole lineage with --from-root
--------------------------------------

*Point at any row (or an artifact) and erase the entire call/produced tree it belongs to, both up to the root and back down.*

**APIs:** ``remove:artifact``, ``remove:job``

.. include:: /stitch/recipes/erase-a-whole-lineage-with-from-root.rst

.. _stitch-keep-artifacts-while-pruning-provenance:

Keep the artifacts while pruning provenance
-------------------------------------------

*Erase the database rows and edges of a removal but leave the artifact files on disk, listed under "Left on disk".*

**APIs:** ``remove:job``, ``remove:artifact``

.. include:: /stitch/recipes/keep-artifacts-while-pruning-provenance.rst

.. _stitch-keep-files-database-only-removal:

Remove the records only, keep every file
----------------------------------------

*Erase the database rows and edges of a removal while making no filesystem change at all --- every directory, artifact, and plain output stays.*

**APIs:** ``remove:job``, ``remove:artifact``

.. include:: /stitch/recipes/keep-files-database-only-removal.rst
