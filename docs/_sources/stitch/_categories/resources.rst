Resources
=========

Fetching input artifacts (datasets, source code) and declaring them as command dependencies.

.. _stitch-register-a-resource:

Register a resource type
------------------------

*Declare how to acquire an input artifact with knit_register_resource and a download decorator.*

**APIs:** ``knit_register_resource``, ``knit_with_local``, ``knit_with_git``, ``knit_with_url``

.. include:: /stitch/recipes/register-a-resource.rst

.. _stitch-fetch-a-resource:

Fetch a resource instance
-------------------------

*Acquire a named instance of a resource type with the knit fetch dispatcher.*

**APIs:** ``fetch``

.. include:: /stitch/recipes/fetch-a-resource.rst

.. _stitch-consume-a-resource:

Consume a resource in a command
-------------------------------

*Declare a resource dependency with knit_with_resource and resolve it with knit_resource_path.*

**APIs:** ``knit_with_resource``, ``knit_resource_path``

.. include:: /stitch/recipes/consume-a-resource.rst
