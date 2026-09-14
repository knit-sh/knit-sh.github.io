AI
==

Configuring an AI provider and asking natural-language questions about the experiment.

.. _stitch-configure-the-ai-provider:

Configure the AI provider
-------------------------

*Point knit at an OpenAI-compatible AI provider with bootstrap --ai-* — storing only env-var names, never the key.*

**APIs:** ``bootstrap``

.. include:: /stitch/recipes/configure-the-ai-provider.rst

.. _stitch-ask-a-natural-language-question:

Ask a natural-language question
-------------------------------

*Ask ai ask a plain-English question; the model answers by calling knit's read-only introspection tools — it can inspect, never mutate.*

**APIs:** ``ai:ask``

.. include:: /stitch/recipes/ask-a-natural-language-question.rst

.. _stitch-answer-with-generated-sql:

Answer with a generated query
-----------------------------

*Turn a question into one read-only SQL or Cypher query with ai query — the model writes it, knit runs it read-only and self-corrects on error.*

**APIs:** ``ai:query``

.. include:: /stitch/recipes/answer-with-generated-sql.rst
