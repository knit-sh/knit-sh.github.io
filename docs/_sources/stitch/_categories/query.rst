Query
=====

Discovering the schema and querying the provenance database with Cypher or read-only SQL.

.. _stitch-discover-the-schema:

Discover the schema
-------------------

*List the database's tables and columns, or validate a reference, with query catalog before writing a query.*

**APIs:** ``query:catalog``

.. include:: /stitch/recipes/discover-the-schema.rst

.. _stitch-query-the-provenance-graph:

Query the provenance graph
--------------------------

*Run read-only Cypher over the provenance graph with query graph — nodes are tables, edges are call and used_by relationships.*

**APIs:** ``query:graph``, ``knit_as``

.. include:: /stitch/recipes/query-the-provenance-graph.rst

.. _stitch-run-raw-sql:

Run raw SQL
-----------

*Run a read-only SQL query with query sql, and shape any query's output with the shared --format, --header, and --separator options.*

**APIs:** ``query:sql``

.. include:: /stitch/recipes/run-raw-sql.rst

.. _stitch-query-across-platforms:

Query across platforms
----------------------

*Query the current database together with other platforms' databases at read time with --extra, and tag every row by the platform it ran on.*

**APIs:** ``query:graph``, ``query:sql``

.. include:: /stitch/recipes/query-across-platforms.rst

.. _stitch-trace-an-artifact-to-its-producer:

Trace an artifact back to its producer
--------------------------------------

*Recover which invocation produced a file by walking the produced edge from its artifacts row back to the producing command.*

**APIs:** ``query:graph``, ``query:sql``, ``knit_with_output_artifact``

.. include:: /stitch/recipes/trace-an-artifact-to-its-producer.rst

.. _stitch-walk-artifact-lineage:

Walk an artifact's full lineage
-------------------------------

*Walk producer --produced--> artifact --used_by--> consumer in one query by joining the two provenance edges on the artifact's row.*

**APIs:** ``query:graph``, ``query:sql``, ``knit_with_input_artifact``, ``knit_with_output_artifact``

.. include:: /stitch/recipes/walk-artifact-lineage.rst
