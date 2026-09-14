Profiles
========

Selecting a machine profile at bootstrap and reading its scheduler, launcher, and hardware fields.

.. _stitch-select-a-machine-profile:

Select a machine profile
------------------------

*Pass bootstrap --profile to prepopulate scheduler, launcher, and hardware defaults from a shared machine description.*

**APIs:** ``bootstrap``, ``profile:list``, ``profile:show``

.. include:: /stitch/recipes/select-a-machine-profile.rst

.. _stitch-read-a-profile-field:

Read a profile field in a script
--------------------------------

*Call knit_get_profile_field with a jq path to read any field from the bootstrapped machine profile inside a command body.*

**APIs:** ``knit_get_profile_field``, ``knit_list_profiles``

.. include:: /stitch/recipes/read-a-profile-field.rst

.. _stitch-read-the-platform-name:

Read the platform name in a script
----------------------------------

*Call knit_platform_name to get the human-facing name of the machine the experiment was bootstrapped for.*

**APIs:** ``knit_platform_name``

.. include:: /stitch/recipes/read-the-platform-name.rst

.. _stitch-example-machine-profile:

Anatomy of a machine profile
----------------------------

*A walkthrough of a real profile (ALCF Polaris) — its scheduler, launcher, hardware, modules, and Spack sections.*

**APIs:** ``bootstrap``, ``profile:show``

.. include:: /stitch/recipes/example-machine-profile.rst

.. _stitch-write-a-machine-profile:

Write a machine profile
-----------------------

*Guidance for profile authors — capture only what the experiment cannot do itself, and keep the Spack section to vendor packages.*

**APIs:** ``bootstrap``, ``knit_with_spack_specs``

.. include:: /stitch/recipes/write-a-machine-profile.rst
