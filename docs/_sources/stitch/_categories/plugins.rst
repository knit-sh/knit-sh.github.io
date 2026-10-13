Plugins
=======

Importing plugins and authoring your own: commands, decorators, shorthands, and command extensions.

.. _stitch-import-a-plugin:

Import a plugin
---------------

*Add a plugin to an experiment with knit_import, pinned to a ref.*

**APIs:** ``knit_import``

.. include:: /stitch/recipes/import-a-plugin.rst

.. _stitch-author-a-decorator:

Author a decorator
------------------

*Build a decorator from the public registration surface.*

**APIs:** ``knit_run_before``, ``knit_add_command_note``, ``knit_command_set_marker``, ``knit_command_has_marker``, ``knit_current_command``

.. include:: /stitch/recipes/author-a-decorator.rst

.. _stitch-register-a-shorthand:

Register a shorthand
--------------------

*Expose a decorator as an @-shorthand for the user's experiment.*

**APIs:** ``knit_register_shorthand``

.. include:: /stitch/recipes/register-a-shorthand.rst

.. _stitch-extend-a-command:

Extend a command
----------------

*Reopen a registered command to add options or hooks with knit_extend.*

**APIs:** ``knit_extend``, ``knit_ensure_subcommand_exists``

.. include:: /stitch/recipes/extend-a-command.rst
