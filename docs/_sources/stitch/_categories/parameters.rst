Parameters
==========

Declaring parameters, flags, extras, and reusable parameter sets.

.. _stitch-required-parameter:

Add a required parameter
------------------------

*Declare a parameter the caller must supply and read it in the body.*

**APIs:** ``knit_with_required``, ``knit_get_parameter``

.. include:: /stitch/recipes/required-parameter.rst

.. _stitch-positional-arguments:

Positional arguments
--------------------

*Why Knit has no positional parameters, and what to write instead.*

**APIs:** ``knit_with_required``

.. include:: /stitch/recipes/positional-arguments.rst

.. _stitch-optional-parameters-and-flags:

Optional parameters and flags
-----------------------------

*Give a parameter a default, or declare a boolean flag.*

**APIs:** ``knit_with_optional``, ``knit_with_flag``, ``knit_get_parameter``

.. include:: /stitch/recipes/optional-parameters-and-flags.rst

.. _stitch-env-default-parameter:

Default a parameter from the environment
----------------------------------------

*Fall back to an environment variable when a parameter is omitted.*

**APIs:** ``knit_with_optional``

.. include:: /stitch/recipes/env-default-parameter.rst

.. _stitch-reuse-parameters-parameter-set:

Reuse parameters with a parameter set
-------------------------------------

*Declare a group of parameters once and import it into many commands.*

**APIs:** ``knit_parameter_set``, ``knit_with_parameter_set``, ``knit_with_required``

.. include:: /stitch/recipes/reuse-parameters-parameter-set.rst

.. _stitch-import-only-some-parameters:

Import only some parameters of a set
------------------------------------

*Import just a few of a parameter set's parameters with --only.*

**APIs:** ``knit_with_parameter_set``, ``knit_parameter_set``

.. include:: /stitch/recipes/import-only-some-parameters.rst

.. _stitch-exclude-parameters-from-a-set:

Exclude parameters when importing a set
---------------------------------------

*Import a parameter set minus a few parameters, freeing those names to re-declare.*

**APIs:** ``knit_with_parameter_set``, ``knit_parameter_set``, ``knit_with_optional``

.. include:: /stitch/recipes/exclude-parameters-from-a-set.rst

.. _stitch-pass-trailing-arguments:

Pass opaque trailing arguments
------------------------------

*Accept arbitrary arguments after -- and read them in the body.*

**APIs:** ``knit_with_extra``, ``knit_extra_index``

.. include:: /stitch/recipes/pass-trailing-arguments.rst

.. _stitch-validate-plain-function-args:

Validate args in a plain function
---------------------------------

*Reject unexpected arguments in a helper that is not a registered command.*

**APIs:** ``knit_check_arguments``, ``knit_get_parameter``

.. include:: /stitch/recipes/validate-plain-function-args.rst
