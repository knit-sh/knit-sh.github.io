Public API
==========

The public API is the stable interface of Knit. These functions and
variables have names without a leading underscore and are intended to
remain backwards compatible across releases.

Functions
---------

.. doxygenfunction:: knit
   :project: knit

.. doxygenfunction:: knit_artifact
   :project: knit

.. doxygenfunction:: knit_artifact_dir
   :project: knit

.. doxygenfunction:: knit_as
   :project: knit

.. doxygenfunction:: knit_bundle_requires
   :project: knit

.. doxygenfunction:: knit_check_arguments
   :project: knit

.. doxygenfunction:: knit_critical
   :project: knit

.. doxygenfunction:: knit_debug
   :project: knit

.. doxygenfunction:: knit_done
   :project: knit

.. doxygenfunction:: knit_empty
   :project: knit

.. doxygenfunction:: knit_enum
   :project: knit

.. doxygenfunction:: knit_enum_values
   :project: knit

.. doxygenfunction:: knit_error
   :project: knit

.. doxygenfunction:: knit_extra_index
   :project: knit

.. doxygenfunction:: knit_fatal
   :project: knit

.. doxygenfunction:: knit_framed
   :project: knit

.. doxygenfunction:: knit_get_parameter
   :project: knit

.. doxygenfunction:: knit_get_profile_field
   :project: knit

.. doxygenfunction:: knit_hidden
   :project: knit

.. doxygenfunction:: knit_hidden_if
   :project: knit

.. doxygenfunction:: knit_hidden_if_not_usable
   :project: knit

.. doxygenfunction:: knit_highlight_if
   :project: knit

.. doxygenfunction:: knit_info
   :project: knit

.. doxygenfunction:: knit_input_artifact_path
   :project: knit

.. doxygenfunction:: knit_input_artifact_paths
   :project: knit

.. doxygenfunction:: knit_job_hostnames
   :project: knit

.. doxygenfunction:: knit_job_nodecount
   :project: knit

.. doxygenfunction:: knit_list_profiles
   :project: knit

.. doxygenfunction:: knit_log_set_level
   :project: knit

.. doxygenfunction:: knit_no_record_on_failure
   :project: knit

.. doxygenfunction:: knit_output
   :project: knit

.. doxygenfunction:: knit_parameter_set
   :project: knit

.. doxygenfunction:: knit_platform_name
   :project: knit

.. doxygenfunction:: knit_popd
   :project: knit

.. doxygenfunction:: knit_provides_launcher
   :project: knit

.. doxygenfunction:: knit_pushd
   :project: knit

.. doxygenfunction:: knit_register
   :project: knit

.. doxygenfunction:: knit_register_app
   :project: knit

.. doxygenfunction:: knit_register_artifact
   :project: knit

.. doxygenfunction:: knit_register_job
   :project: knit

.. doxygenfunction:: knit_register_resource
   :project: knit

.. doxygenfunction:: knit_register_setup
   :project: knit

.. doxygenfunction:: knit_register_wrapper
   :project: knit

.. doxygenfunction:: knit_resource_path
   :project: knit

.. doxygenfunction:: knit_set_program_description
   :project: knit

.. doxygenfunction:: knit_setup_activate_line
   :project: knit

.. doxygenfunction:: knit_setup_env_append
   :project: knit

.. doxygenfunction:: knit_setup_env_prepend
   :project: knit

.. doxygenfunction:: knit_setup_env_set
   :project: knit

.. doxygenfunction:: knit_setup_env_unset
   :project: knit

.. doxygenfunction:: knit_trace
   :project: knit

.. doxygenfunction:: knit_type_check
   :project: knit

.. doxygenfunction:: knit_type_exists
   :project: knit

.. doxygenfunction:: knit_usable_before_bootstrap
   :project: knit

.. doxygenfunction:: knit_usable_if
   :project: knit

.. doxygenfunction:: knit_warning
   :project: knit

.. doxygenfunction:: knit_with_checksum
   :project: knit

.. doxygenfunction:: knit_with_dispatch
   :project: knit

.. doxygenfunction:: knit_with_extra
   :project: knit

.. doxygenfunction:: knit_with_flag
   :project: knit

.. doxygenfunction:: knit_with_git
   :project: knit

.. doxygenfunction:: knit_with_input_artifact
   :project: knit

.. doxygenfunction:: knit_with_local
   :project: knit

.. doxygenfunction:: knit_with_optional
   :project: knit

.. doxygenfunction:: knit_with_output
   :project: knit

.. doxygenfunction:: knit_with_output_artifact
   :project: knit

.. doxygenfunction:: knit_with_parameter_set
   :project: knit

.. doxygenfunction:: knit_with_provenance
   :project: knit

.. doxygenfunction:: knit_with_required
   :project: knit

.. doxygenfunction:: knit_with_resource
   :project: knit

.. doxygenfunction:: knit_with_setup
   :project: knit

.. doxygenfunction:: knit_with_spack_env
   :project: knit

.. doxygenfunction:: knit_with_spack_specs
   :project: knit

.. doxygenfunction:: knit_with_subcommand_title
   :project: knit

.. doxygenfunction:: knit_with_table
   :project: knit

.. doxygenfunction:: knit_with_url
   :project: knit

.. doxygenfunction:: knit_without_provenance
   :project: knit

.. doxygenfunction:: knit_without_setup
   :project: knit

Variables
---------

.. doxygenvariable:: KNIT_IGNORE_CHECKSUM
   :project: knit

.. doxygenvariable:: KNIT_JOB_PREFIX
   :project: knit

.. doxygenvariable:: KNIT_LOG_LEVEL
   :project: knit

.. doxygenvariable:: KNIT_MPI_LOCAL_RANK
   :project: knit

.. doxygenvariable:: KNIT_MPI_RANK
   :project: knit

.. doxygenvariable:: KNIT_MPI_SIZE
   :project: knit

.. doxygenvariable:: KNIT_RESOURCE_EXPECTED_CHECKSUM
   :project: knit

.. doxygenvariable:: KNIT_RESOURCE_PREFIX
   :project: knit

.. doxygenvariable:: KNIT_SCRIPT_NAME
   :project: knit

.. doxygenvariable:: KNIT_SCRIPT_PATH
   :project: knit

.. doxygenvariable:: KNIT_SETUP_PREFIX
   :project: knit

.. doxygenvariable:: KNIT_VERSION
   :project: knit
