Logging & output
================

Emitting messages at the right level and framing a long-running command's output.

.. _stitch-log-at-the-right-level:

Log at the right level
----------------------

*Narrate a command with knit_trace/debug/info/warning/error/critical and control verbosity with KNIT_LOG_LEVEL or knit_log_set_level.*

**APIs:** ``knit_trace``, ``knit_debug``, ``knit_info``, ``knit_warning``, ``knit_error``, ``knit_critical``, ``knit_fatal``, ``knit_log_set_level``, ``KNIT_LOG_LEVEL``

.. include:: /stitch/recipes/log-at-the-right-level.rst

.. _stitch-frame-a-long-running-command:

Frame a long-running command
----------------------------

*Pipe a noisy command's output into knit_framed to keep it inside a fixed scrolling box, with safe non-TTY passthrough.*

**APIs:** ``knit_framed``

.. include:: /stitch/recipes/frame-a-long-running-command.rst
