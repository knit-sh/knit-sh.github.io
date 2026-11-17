Claims
======

Stating a plain-English finding as an executable claim, checking it against the recorded data, and recording the verdict.

.. _stitch-declare-an-executable-claim:

Declare an executable claim
---------------------------

*State a plain-English finding as a @claim whose checker decides it against the recorded data and returns a three-valued verdict.*

**APIs:** ``knit_register_claim``, ``knit_with_optional``, ``knit_with_output``, ``knit_output``, ``KNIT_CLAIM_HOLDS``, ``KNIT_CLAIM_REFUTED``, ``KNIT_CLAIM_INSUFFICIENT``, ``claim:check``, ``claim:list``

.. include:: /stitch/recipes/declare-an-executable-claim.rst
