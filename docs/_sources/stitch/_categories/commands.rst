Commands
========

Registering commands, subcommands, and dispatchers.

.. _stitch-command-script-skeleton:

The experiment script skeleton
------------------------------

*The minimal top-and-tail every Knit experiment script needs.*

**APIs:** ``knit``, ``KNIT_SCRIPT_NAME``

.. include:: /stitch/recipes/command-script-skeleton.rst

.. _stitch-register-a-command:

Register a command
------------------

*Declare a command with knit_register, a body function, and knit_done.*

**APIs:** ``knit_register``, ``knit_done``, ``knit_empty``

.. include:: /stitch/recipes/register-a-command.rst

.. _stitch-set-program-description:

Set the program description
---------------------------

*Give the experiment a one-line description shown in top-level --help.*

**APIs:** ``knit_set_program_description``

.. include:: /stitch/recipes/set-program-description.rst

.. _stitch-nest-subcommands:

Nest subcommands
----------------

*Group commands under a parent using colon-nested names.*

**APIs:** ``knit_register``, ``knit_empty``, ``knit_with_subcommand_title``

.. include:: /stitch/recipes/nest-subcommands.rst

.. _stitch-add-a-dispatcher:

Add a dispatcher command
------------------------

*Forward the trailing arguments to a target the command resolves itself.*

**APIs:** ``knit_with_dispatch``, ``knit_extra_index``

.. include:: /stitch/recipes/add-a-dispatcher.rst

.. _stitch-hide-or-gate-a-command:

Hide or gate a command
----------------------

*Control a command's visibility in --help and whether it may run.*

**APIs:** ``knit_hidden``, ``knit_hidden_if``, ``knit_usable_if``, ``knit_usable_before_bootstrap``

.. include:: /stitch/recipes/hide-or-gate-a-command.rst

.. _stitch-highlight-a-command:

Highlight a command in --help
-----------------------------

*Bold a command's name in --help when a predicate holds.*

**APIs:** ``knit_highlight_if``

.. include:: /stitch/recipes/highlight-a-command.rst
