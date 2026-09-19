Private API
===========

The private API consists of names with one or two leading underscores,
grouped below by the source file that defines them. It is internal to
Knit and may change at any time, without notice and without a
compatibility guarantee.

ai.sh
-----

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_ai_chat_request
   :project: knit

.. doxygenfunction:: _knit_ai_default_system_prompt
   :project: knit

.. doxygenfunction:: _knit_ai_describe_summary
   :project: knit

.. doxygenfunction:: _knit_ai_dispatch_tool
   :project: knit

.. doxygenfunction:: _knit_ai_loop
   :project: knit

.. doxygenfunction:: _knit_ai_resolve_config
   :project: knit

.. doxygenfunction:: _knit_ai_sql_is_readonly
   :project: knit

.. doxygenfunction:: _knit_ai_store_config
   :project: knit

.. doxygenfunction:: _knit_ai_tool_db_query
   :project: knit

.. doxygenfunction:: _knit_ai_tool_describe
   :project: knit

.. doxygenfunction:: _knit_ai_tool_help
   :project: knit

.. doxygenfunction:: _knit_ai_tool_job_output
   :project: knit

.. doxygenfunction:: _knit_ai_tool_metadata_show
   :project: knit

.. doxygenfunction:: _knit_ai_tools_schema
   :project: knit

.. doxygenfunction:: _knit_ai_truncate
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_AI_DEFAULT_BASE_URL
   :project: knit

.. doxygenvariable:: _KNIT_AI_TOOL_OUTPUT_MAX_BYTES
   :project: knit

app.sh
------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_app_before_cb
   :project: knit

.. doxygenfunction:: _knit_run
   :project: knit

.. doxygenfunction:: _knit_run_checksum_inputs
   :project: knit

.. doxygenfunction:: _knit_run_checksum_outputs
   :project: knit

.. doxygenfunction:: _knit_run_delete_row
   :project: knit

.. doxygenfunction:: _knit_run_normalize_mpi_env
   :project: knit

.. doxygenfunction:: _knit_run_record_exit_status
   :project: knit

.. doxygenfunction:: _knit_run_resolve_placement
   :project: knit

.. doxygenfunction:: _knit_run_worker
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_APPS
   :project: knit

.. doxygenvariable:: _KNIT_RUNS_TABLE
   :project: knit

artifact.sh
-----------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_artifact_cardinality_phrase
   :project: knit

.. doxygenfunction:: _knit_artifact_check_lower_bound
   :project: knit

.. doxygenfunction:: _knit_artifact_ensure_table_cb
   :project: knit

.. doxygenfunction:: _knit_artifact_is_bound
   :project: knit

.. doxygenfunction:: _knit_artifact_kind_type
   :project: knit

.. doxygenfunction:: _knit_artifact_parse_kind
   :project: knit

.. doxygenfunction:: _knit_artifact_require_table
   :project: knit

.. doxygenfunction:: _knit_artifact_resolve_path
   :project: knit

.. doxygenfunction:: _knit_artifact_root
   :project: knit

.. doxygenfunction:: _knit_artifacts_create_table
   :project: knit

.. doxygenfunction:: _knit_artifacts_ensure_table
   :project: knit

.. doxygenfunction:: _knit_artifacts_path_recorded
   :project: knit

.. doxygenfunction:: _knit_artifacts_record_sql
   :project: knit

.. doxygenfunction:: _knit_artifacts_row_sql
   :project: knit

.. doxygenfunction:: _knit_input_artifact_after_cb
   :project: knit

.. doxygenfunction:: _knit_input_artifact_before_cb
   :project: knit

.. doxygenfunction:: _knit_input_artifact_param_kind
   :project: knit

.. doxygenfunction:: _knit_input_artifact_quantifier
   :project: knit

.. doxygenfunction:: _knit_input_artifact_record_used_by_edge
   :project: knit

.. doxygenfunction:: _knit_input_artifact_resolve_list
   :project: knit

.. doxygenfunction:: _knit_input_artifact_validate_one
   :project: knit

.. doxygenfunction:: _knit_output_artifact_quantifier
   :project: knit

.. doxygenfunction:: _knit_register_artifact
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_ARTIFACTS_TABLE
   :project: knit

.. doxygenvariable:: _KNIT_ARTIFACTS_TABLE_ENSURED
   :project: knit

.. doxygenvariable:: _KNIT_ARTIFACT_KINDS
   :project: knit

.. doxygenvariable:: _KNIT_ARTIFACT_KIND_DESCRIPTIONS
   :project: knit

boostrap.sh
-----------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_bootstrap
   :project: knit

.. doxygenfunction:: _knit_bootstrap_check_prerequisites
   :project: knit

.. doxygenfunction:: _knit_bootstrap_dir_has_subdir
   :project: knit

.. doxygenfunction:: _knit_bootstrap_jobs_recorded
   :project: knit

.. doxygenfunction:: _knit_bootstrap_on_exit
   :project: knit

.. doxygenfunction:: _knit_bootstrap_relocate_path
   :project: knit

.. doxygenfunction:: _knit_bootstrap_update
   :project: knit

.. doxygenfunction:: _knit_bootstrap_update_meta
   :project: knit

.. doxygenfunction:: _knit_bootstrap_update_profile
   :project: knit

.. doxygenfunction:: _knit_bootstrap_warn_absolute_root
   :project: knit

.. doxygenfunction:: _knit_highlight_if_not_bootstrapped
   :project: knit

.. doxygenfunction:: _knit_is_bootstrapped
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_IS_BOOTSTRAPPED
   :project: knit

.. doxygenvariable:: _KNIT_PREFIX
   :project: knit

bundle.sh
---------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_bundle
   :project: knit

.. doxygenfunction:: _knit_bundle_auto_require
   :project: knit

.. doxygenfunction:: _knit_bundle_collect
   :project: knit

.. doxygenfunction:: _knit_bundle_default_output
   :project: knit

.. doxygenfunction:: _knit_bundle_escapes_root
   :project: knit

.. doxygenfunction:: _knit_bundle_expand_requires
   :project: knit

.. doxygenfunction:: _knit_bundle_is_glob
   :project: knit

.. doxygenfunction:: _knit_bundle_print_list
   :project: knit

.. doxygenfunction:: _knit_bundle_print_tree
   :project: knit

.. doxygenfunction:: _knit_bundle_prune_paths
   :project: knit

.. doxygenfunction:: _knit_bundle_relpath
   :project: knit

.. doxygenfunction:: _knit_bundle_render_tree
   :project: knit

.. doxygenfunction:: _knit_bundle_source
   :project: knit

.. doxygenfunction:: _knit_bundle_warn_unselected_local
   :project: knit

.. doxygenfunction:: _knit_bundle_write_archive
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_BUNDLE_AUTO_REQUIRES
   :project: knit

.. doxygenvariable:: _KNIT_BUNDLE_EXTERN
   :project: knit

.. doxygenvariable:: _KNIT_BUNDLE_REQUIRES
   :project: knit

cli.sh
------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_arg_name
   :project: knit

.. doxygenfunction:: _knit_arg_was_provided
   :project: knit

.. doxygenfunction:: _knit_build_constraint_json
   :project: knit

.. doxygenfunction:: _knit_check_argument_type
   :project: knit

.. doxygenfunction:: _knit_check_command_arguments
   :project: knit

.. doxygenfunction:: _knit_check_constraints
   :project: knit

.. doxygenfunction:: _knit_checksum_inputs
   :project: knit

.. doxygenfunction:: _knit_checksum_is_app_worker
   :project: knit

.. doxygenfunction:: _knit_checksum_outputs
   :project: knit

.. doxygenfunction:: _knit_checksum_require_exists
   :project: knit

.. doxygenfunction:: _knit_checksum_stash
   :project: knit

.. doxygenfunction:: _knit_checksum_stash_from_env
   :project: knit

.. doxygenfunction:: _knit_checksum_target_exists
   :project: knit

.. doxygenfunction:: _knit_command_check_usable
   :project: knit

.. doxygenfunction:: _knit_command_demangle
   :project: knit

.. doxygenfunction:: _knit_command_display
   :project: knit

.. doxygenfunction:: _knit_command_get_last
   :project: knit

.. doxygenfunction:: _knit_command_get_parents
   :project: knit

.. doxygenfunction:: _knit_command_hidden
   :project: knit

.. doxygenfunction:: _knit_command_highlighted
   :project: knit

.. doxygenfunction:: _knit_command_is_builtin
   :project: knit

.. doxygenfunction:: _knit_command_is_usable_before_bootstrap
   :project: knit

.. doxygenfunction:: _knit_command_is_wrapper
   :project: knit

.. doxygenfunction:: _knit_command_mangle
   :project: knit

.. doxygenfunction:: _knit_command_with_space
   :project: knit

.. doxygenfunction:: _knit_decl_flag_present
   :project: knit

.. doxygenfunction:: _knit_execute_after_commands
   :project: knit

.. doxygenfunction:: _knit_execute_before_commands
   :project: knit

.. doxygenfunction:: _knit_expand_command_arguments
   :project: knit

.. doxygenfunction:: _knit_find_flag
   :project: knit

.. doxygenfunction:: _knit_format_option_alternatives
   :project: knit

.. doxygenfunction:: _knit_help_render_entry
   :project: knit

.. doxygenfunction:: _knit_hidden_if_not_usable_pred
   :project: knit

.. doxygenfunction:: _knit_invoke_command
   :project: knit

.. doxygenfunction:: _knit_is_builtin
   :project: knit

.. doxygenfunction:: _knit_name_is_valid
   :project: knit

.. doxygenfunction:: _knit_name_normalize
   :project: knit

.. doxygenfunction:: _knit_output_default
   :project: knit

.. doxygenfunction:: _knit_output_description
   :project: knit

.. doxygenfunction:: _knit_output_type
   :project: knit

.. doxygenfunction:: _knit_param_check_declaration
   :project: knit

.. doxygenfunction:: _knit_param_default
   :project: knit

.. doxygenfunction:: _knit_param_description
   :project: knit

.. doxygenfunction:: _knit_param_type
   :project: knit

.. doxygenfunction:: _knit_print_command_usage
   :project: knit

.. doxygenfunction:: _knit_print_options_block
   :project: knit

.. doxygenfunction:: _knit_provenance_enabled
   :project: knit

.. doxygenfunction:: _knit_pset_filter_build
   :project: knit

.. doxygenfunction:: _knit_pset_import_skip
   :project: knit

.. doxygenfunction:: _knit_push_done_cb
   :project: knit

.. doxygenfunction:: _knit_record_invocation
   :project: knit

.. doxygenfunction:: _knit_record_row_now
   :project: knit

.. doxygenfunction:: _knit_register_checksum
   :project: knit

.. doxygenfunction:: _knit_register_fileparam
   :project: knit

.. doxygenfunction:: _knit_register_result
   :project: knit

.. doxygenfunction:: _knit_reserve_name
   :project: knit

.. doxygenfunction:: _knit_resolve_default
   :project: knit

.. doxygenfunction:: _knit_resolve_row_id
   :project: knit

.. doxygenfunction:: _knit_resolve_source_context
   :project: knit

.. doxygenfunction:: _knit_run_after
   :project: knit

.. doxygenfunction:: _knit_run_before
   :project: knit

.. doxygenfunction:: _knit_set_row_id
   :project: knit

.. doxygenfunction:: _knit_usable_before_bootstrap_validate
   :project: knit

.. doxygenfunction:: _knit_without_exit_status
   :project: knit

.. doxygenfunction:: _knit_wrapper_reject_declaration
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_CALL_ALIAS
   :project: knit

.. doxygenvariable:: _KNIT_COMMANDS
   :project: knit

.. doxygenvariable:: _KNIT_EXECUTING_ALIAS
   :project: knit

.. doxygenvariable:: _KNIT_EXECUTING_COMMAND
   :project: knit

.. doxygenvariable:: _KNIT_EXECUTING_ROW_ID
   :project: knit

.. doxygenvariable:: _KNIT_EXECUTING_START_TIME
   :project: knit

.. doxygenvariable:: _KNIT_INVOCATION_END_TIME
   :project: knit

.. doxygenvariable:: _KNIT_INVOCATION_EXIT_STATUS
   :project: knit

.. doxygenvariable:: _KNIT_INVOCATION_RAW_ARGS
   :project: knit

.. doxygenvariable:: _KNIT_LAST_ROW_ID
   :project: knit

.. doxygenvariable:: _KNIT_PARAMETER_SETS
   :project: knit

.. doxygenvariable:: _KNIT_RECORDING_SUPPRESSED
   :project: knit

.. doxygenvariable:: _KNIT_ROOT_COMMANDS
   :project: knit

.. doxygenvariable:: _KNIT_USED_ALIASES
   :project: knit

db.sh
-----

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_db_check_table
   :project: knit

.. doxygenfunction:: _knit_db_command_has_exit_status
   :project: knit

.. doxygenfunction:: _knit_db_create_table
   :project: knit

.. doxygenfunction:: _knit_db_migrate_table
   :project: knit

.. doxygenfunction:: _knit_db_record_invocation
   :project: knit

.. doxygenfunction:: _knit_db_setup_table
   :project: knit

.. doxygenfunction:: _knit_db_sql_ident
   :project: knit

.. doxygenfunction:: _knit_db_type_default
   :project: knit

.. doxygenfunction:: _knit_db_update_row
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_DB_REGISTERED_TABLES
   :project: knit

describe.sh
-----------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_describe
   :project: knit

.. doxygenfunction:: _knit_describe_children
   :project: knit

.. doxygenfunction:: _knit_describe_command_kind
   :project: knit

.. doxygenfunction:: _knit_describe_default
   :project: knit

.. doxygenfunction:: _knit_describe_default_artifacts
   :project: knit

.. doxygenfunction:: _knit_describe_default_command
   :project: knit

.. doxygenfunction:: _knit_describe_default_heading
   :project: knit

.. doxygenfunction:: _knit_describe_default_options
   :project: knit

.. doxygenfunction:: _knit_describe_default_outputs
   :project: knit

.. doxygenfunction:: _knit_describe_emit
   :project: knit

.. doxygenfunction:: _knit_describe_emit_array
   :project: knit

.. doxygenfunction:: _knit_describe_emit_object
   :project: knit

.. doxygenfunction:: _knit_describe_enum_constraint
   :project: knit

.. doxygenfunction:: _knit_describe_enum_values_json
   :project: knit

.. doxygenfunction:: _knit_describe_filter_on
   :project: knit

.. doxygenfunction:: _knit_describe_implementation
   :project: knit

.. doxygenfunction:: _knit_describe_is_result
   :project: knit

.. doxygenfunction:: _knit_describe_is_selected
   :project: knit

.. doxygenfunction:: _knit_describe_json
   :project: knit

.. doxygenfunction:: _knit_describe_json_artifact
   :project: knit

.. doxygenfunction:: _knit_describe_json_artifacts
   :project: knit

.. doxygenfunction:: _knit_describe_json_command
   :project: knit

.. doxygenfunction:: _knit_describe_json_compact
   :project: knit

.. doxygenfunction:: _knit_describe_json_enums
   :project: knit

.. doxygenfunction:: _knit_describe_json_escape
   :project: knit

.. doxygenfunction:: _knit_describe_json_output
   :project: knit

.. doxygenfunction:: _knit_describe_json_outputs
   :project: knit

.. doxygenfunction:: _knit_describe_json_param
   :project: knit

.. doxygenfunction:: _knit_describe_json_params
   :project: knit

.. doxygenfunction:: _knit_describe_json_str
   :project: knit

.. doxygenfunction:: _knit_describe_markdown
   :project: knit

.. doxygenfunction:: _knit_describe_md_artifacts
   :project: knit

.. doxygenfunction:: _knit_describe_md_cell
   :project: knit

.. doxygenfunction:: _knit_describe_md_code
   :project: knit

.. doxygenfunction:: _knit_describe_md_command
   :project: knit

.. doxygenfunction:: _knit_describe_md_constraints
   :project: knit

.. doxygenfunction:: _knit_describe_md_outputs
   :project: knit

.. doxygenfunction:: _knit_describe_md_params
   :project: knit

.. doxygenfunction:: _knit_describe_read_filters
   :project: knit

.. doxygenfunction:: _knit_describe_should_emit
   :project: knit

.. doxygenfunction:: _knit_describe_visible
   :project: knit

.. doxygenfunction:: _knit_describe_yaml
   :project: knit

.. doxygenfunction:: _knit_describe_yaml_artifact
   :project: knit

.. doxygenfunction:: _knit_describe_yaml_command
   :project: knit

.. doxygenfunction:: _knit_describe_yaml_enums
   :project: knit

.. doxygenfunction:: _knit_describe_yaml_flow_seq
   :project: knit

.. doxygenfunction:: _knit_describe_yaml_needs_quote
   :project: knit

.. doxygenfunction:: _knit_describe_yaml_output
   :project: knit

.. doxygenfunction:: _knit_describe_yaml_param
   :project: knit

.. doxygenfunction:: _knit_describe_yaml_params
   :project: knit

.. doxygenfunction:: _knit_describe_yaml_scalar
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_DESCRIBE_EMITTED
   :project: knit

.. doxygenvariable:: _KNIT_DESCRIBE_FILTERS
   :project: knit

.. doxygenvariable:: _KNIT_DESCRIBE_JSON_CS
   :project: knit

.. doxygenvariable:: _KNIT_DESCRIBE_JSON_IND
   :project: knit

.. doxygenvariable:: _KNIT_DESCRIBE_JSON_NL
   :project: knit

.. doxygenvariable:: _KNIT_DESCRIBE_ONLY
   :project: knit

detect.sh
---------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_command_path
   :project: knit

.. doxygenfunction:: _knit_detect_job_manager
   :project: knit

.. doxygenfunction:: _knit_detect_launcher
   :project: knit

.. doxygenfunction:: _knit_detect_mpi
   :project: knit

.. doxygenfunction:: _knit_detect_mpi_launcher
   :project: knit

.. doxygenfunction:: _knit_detect_node_ncpus
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_DETECTED_JOB_MANAGER
   :project: knit

.. doxygenvariable:: _KNIT_DETECTED_LAUNCHER
   :project: knit

.. doxygenvariable:: _KNIT_DETECTED_MPI
   :project: knit

.. doxygenvariable:: _KNIT_DETECTED_MPI_LAUNCHER
   :project: knit

.. doxygenvariable:: _KNIT_DETECTED_NODE_NCPUS
   :project: knit

global.sh
---------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_stdout_is_terminal
   :project: knit

.. doxygenfunction:: _knit_terminal_width
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_COLORS
   :project: knit

.. doxygenvariable:: _KNIT_IS_BOOTSTRAPPING
   :project: knit

job.sh
------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_command_is_job
   :project: knit

.. doxygenfunction:: _knit_declare_submit_options
   :project: knit

.. doxygenfunction:: _knit_job_after_cb
   :project: knit

.. doxygenfunction:: _knit_job_before_cb
   :project: knit

.. doxygenfunction:: _knit_job_killed_trap
   :project: knit

.. doxygenfunction:: _knit_job_record_hostnames
   :project: knit

.. doxygenfunction:: _knit_job_set_state
   :project: knit

.. doxygenfunction:: _knit_prepare_build
   :project: knit

.. doxygenfunction:: _knit_submit
   :project: knit

.. doxygenfunction:: _knit_submit_cleanup_rejected
   :project: knit

.. doxygenfunction:: _knit_submit_dispatch
   :project: knit

.. doxygenfunction:: _knit_submit_meta_read
   :project: knit

.. doxygenfunction:: _knit_submit_meta_write
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_JOBS
   :project: knit

.. doxygenvariable:: _KNIT_JOBS_TABLE
   :project: knit

launch.sh
---------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_launch_backend
   :project: knit

.. doxygenfunction:: _knit_launch_bind_value
   :project: knit

.. doxygenfunction:: _knit_launch_cmdline
   :project: knit

.. doxygenfunction:: _knit_launch_exec
   :project: knit

launch_flux.sh
--------------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_launch_flux_cmdline
   :project: knit

.. doxygenfunction:: _knit_launch_flux_exec
   :project: knit

launch_mpich.sh
---------------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_launch_mpich_cmdline
   :project: knit

.. doxygenfunction:: _knit_launch_mpich_exec
   :project: knit

launch_none.sh
--------------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_launch_none_cmdline
   :project: knit

.. doxygenfunction:: _knit_launch_none_exec
   :project: knit

.. doxygenfunction:: _knit_launch_none_validate
   :project: knit

launch_openmpi.sh
-----------------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_launch_openmpi_cmdline
   :project: knit

.. doxygenfunction:: _knit_launch_openmpi_env_forward
   :project: knit

.. doxygenfunction:: _knit_launch_openmpi_exec
   :project: knit

.. doxygenfunction:: _knit_launch_openmpi_host_slots
   :project: knit

launch_pals.sh
--------------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_launch_pals_cmdline
   :project: knit

.. doxygenfunction:: _knit_launch_pals_exec
   :project: knit

launch_pbs.sh
-------------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_launch_pbs_cmdline
   :project: knit

.. doxygenfunction:: _knit_launch_pbs_exec
   :project: knit

launch_slurm.sh
---------------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_launch_slurm_cmdline
   :project: knit

.. doxygenfunction:: _knit_launch_slurm_exec
   :project: knit

local.sh
--------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_submit_local
   :project: knit

.. doxygenfunction:: _knit_wait_local
   :project: knit

.. doxygenfunction:: _knit_walltime_to_seconds
   :project: knit

log.sh
------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_ensure_trace_file
   :project: knit

.. doxygenfunction:: _knit_log
   :project: knit

.. doxygenfunction:: _knit_log_level_to_int
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_TRACE_FILE
   :project: knit

main.sh
-------

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_JUMP_TO_DIR
   :project: knit

prepare.sh
----------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_prepare
   :project: knit

.. doxygenfunction:: _knit_prepare_claim_id
   :project: knit

.. doxygenfunction:: _knit_prepare_claim_next
   :project: knit

.. doxygenfunction:: _knit_prepare_release
   :project: knit

.. doxygenfunction:: _knit_prepare_remove
   :project: knit

profile.sh
----------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_load_profile
   :project: knit

.. doxygenfunction:: _knit_profile_admin_entries
   :project: knit

.. doxygenfunction:: _knit_profile_file_description
   :project: knit

.. doxygenfunction:: _knit_profile_github_url
   :project: knit

.. doxygenfunction:: _knit_profile_http_get
   :project: knit

.. doxygenfunction:: _knit_profile_is_hidden
   :project: knit

.. doxygenfunction:: _knit_profile_latest_ref
   :project: knit

.. doxygenfunction:: _knit_profile_list
   :project: knit

.. doxygenfunction:: _knit_profile_parse_index
   :project: knit

.. doxygenfunction:: _knit_profile_show
   :project: knit

.. doxygenfunction:: _knit_render_platform_files
   :project: knit

.. doxygenfunction:: _knit_render_platform_sh
   :project: knit

.. doxygenfunction:: _knit_render_spack_config
   :project: knit

.. doxygenfunction:: _knit_resolve_module_init
   :project: knit

.. doxygenfunction:: _knit_resolve_profile
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_MODULE_INIT_CANDIDATES
   :project: knit

.. doxygenvariable:: _KNIT_PROFILE_ADMIN_DIR
   :project: knit

.. doxygenvariable:: _KNIT_PROFILE_DEFAULT_REF
   :project: knit

.. doxygenvariable:: _KNIT_PROFILE_LAST_HTTP
   :project: knit

.. doxygenvariable:: _KNIT_PROFILE_REPO
   :project: knit

prov.sh
-------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_produced_edge_sql
   :project: knit

.. doxygenfunction:: _knit_prov_create_table
   :project: knit

.. doxygenfunction:: _knit_prov_edge_sql
   :project: knit

.. doxygenfunction:: _knit_prov_ensure_table
   :project: knit

.. doxygenfunction:: _knit_prov_now
   :project: knit

.. doxygenfunction:: _knit_prov_nullable_literal
   :project: knit

.. doxygenfunction:: _knit_prov_record_edge
   :project: knit

.. doxygenfunction:: _knit_record_used_by_edge
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_PROV_TABLE
   :project: knit

.. doxygenvariable:: _KNIT_PROV_TABLE_ENSURED
   :project: knit

query.sh
--------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_query_annotate_catalog
   :project: knit

.. doxygenfunction:: _knit_query_catalog_columns
   :project: knit

.. doxygenfunction:: _knit_query_catalog_graph_tables
   :project: knit

.. doxygenfunction:: _knit_query_catalog_has_column
   :project: knit

.. doxygenfunction:: _knit_query_catalog_is_graph_table
   :project: knit

.. doxygenfunction:: _knit_query_catalog_print_table
   :project: knit

.. doxygenfunction:: _knit_query_catalog_produce
   :project: knit

.. doxygenfunction:: _knit_query_read_output_opts
   :project: knit

.. doxygenfunction:: _knit_query_table_alias
   :project: knit

remove.sh
---------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_remove_append_ids
   :project: knit

.. doxygenfunction:: _knit_remove_build_report
   :project: knit

.. doxygenfunction:: _knit_remove_check_refusal
   :project: knit

.. doxygenfunction:: _knit_remove_check_terminal_jobs
   :project: knit

.. doxygenfunction:: _knit_remove_closure_downward
   :project: knit

.. doxygenfunction:: _knit_remove_closure_from_root
   :project: knit

.. doxygenfunction:: _knit_remove_confirm
   :project: knit

.. doxygenfunction:: _knit_remove_declare_flags
   :project: knit

.. doxygenfunction:: _knit_remove_declare_selectors
   :project: knit

.. doxygenfunction:: _knit_remove_delete_rows
   :project: knit

.. doxygenfunction:: _knit_remove_dispatch
   :project: knit

.. doxygenfunction:: _knit_remove_erase_selection
   :project: knit

.. doxygenfunction:: _knit_remove_failed_ids
   :project: knit

.. doxygenfunction:: _knit_remove_filesystem
   :project: knit

.. doxygenfunction:: _knit_remove_id_in_list
   :project: knit

.. doxygenfunction:: _knit_remove_id_table
   :project: knit

.. doxygenfunction:: _knit_remove_instance_names
   :project: knit

.. doxygenfunction:: _knit_remove_map_ids
   :project: knit

.. doxygenfunction:: _knit_remove_plain_outputs
   :project: knit

.. doxygenfunction:: _knit_remove_print_report
   :project: knit

.. doxygenfunction:: _knit_remove_report_left
   :project: knit

.. doxygenfunction:: _knit_remove_require_one_selector
   :project: knit

.. doxygenfunction:: _knit_remove_resolve_by_group
   :project: knit

.. doxygenfunction:: _knit_remove_resolve_by_id
   :project: knit

.. doxygenfunction:: _knit_remove_resolve_by_name
   :project: knit

.. doxygenfunction:: _knit_remove_resolve_by_path
   :project: knit

.. doxygenfunction:: _knit_remove_resolve_by_type
   :project: knit

.. doxygenfunction:: _knit_remove_resolve_selection
   :project: knit

.. doxygenfunction:: _knit_remove_rm_artifact
   :project: knit

.. doxygenfunction:: _knit_remove_rmtree
   :project: knit

.. doxygenfunction:: _knit_remove_row_value
   :project: knit

.. doxygenfunction:: _knit_remove_table_kind
   :project: knit

.. doxygenfunction:: _knit_remove_tables_of_kind
   :project: knit

.. doxygenfunction:: _knit_remove_toplevel
   :project: knit

resource.sh
-----------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_command_is_resource
   :project: knit

.. doxygenfunction:: _knit_fetch
   :project: knit

.. doxygenfunction:: _knit_fetch_git
   :project: knit

.. doxygenfunction:: _knit_fetch_local
   :project: knit

.. doxygenfunction:: _knit_fetch_url
   :project: knit

.. doxygenfunction:: _knit_resource_check_method
   :project: knit

.. doxygenfunction:: _knit_resource_check_sha
   :project: knit

.. doxygenfunction:: _knit_resource_cleanup_dir
   :project: knit

.. doxygenfunction:: _knit_resource_defaults_used
   :project: knit

.. doxygenfunction:: _knit_resource_dep_after_cb
   :project: knit

.. doxygenfunction:: _knit_resource_dep_before_cb
   :project: knit

.. doxygenfunction:: _knit_resource_fetch_body
   :project: knit

.. doxygenfunction:: _knit_resource_make_readonly
   :project: knit

.. doxygenfunction:: _knit_resource_param_type
   :project: knit

.. doxygenfunction:: _knit_resource_record_used_by_edge
   :project: knit

.. doxygenfunction:: _knit_resource_require_registration
   :project: knit

.. doxygenfunction:: _knit_resource_root
   :project: knit

.. doxygenfunction:: _knit_resource_set_method
   :project: knit

.. doxygenfunction:: _knit_resource_source_identity
   :project: knit

.. doxygenfunction:: _knit_sha256
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_RESOURCES
   :project: knit

rocrate.sh
----------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_bundle_rocrate_generate
   :project: knit

.. doxygenfunction:: _knit_export_rocrate
   :project: knit

.. doxygenfunction:: _knit_rocrate_edges_json
   :project: knit

.. doxygenfunction:: _knit_rocrate_encoding_format
   :project: knit

.. doxygenfunction:: _knit_rocrate_files_json
   :project: knit

.. doxygenfunction:: _knit_rocrate_outputs_json
   :project: knit

.. doxygenfunction:: _knit_rocrate_rows_json
   :project: knit

.. doxygenfunction:: _knit_rocrate_table_exists
   :project: knit

sched.sh
--------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_sched_backend
   :project: knit

.. doxygenfunction:: _knit_sched_cancel
   :project: knit

.. doxygenfunction:: _knit_sched_directives
   :project: knit

.. doxygenfunction:: _knit_sched_hostfile
   :project: knit

.. doxygenfunction:: _knit_sched_pick_queue
   :project: knit

.. doxygenfunction:: _knit_sched_profile_field
   :project: knit

.. doxygenfunction:: _knit_sched_resolve
   :project: knit

.. doxygenfunction:: _knit_sched_submit
   :project: knit

.. doxygenfunction:: _knit_sched_submit_cmdline
   :project: knit

.. doxygenfunction:: _knit_sched_wait
   :project: knit

.. doxygenfunction:: _knit_sched_write_jobscript
   :project: knit

.. doxygenfunction:: _knit_uuidv7
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_SCHED_KILL_WARNING_SEC
   :project: knit

.. doxygenvariable:: _KNIT_SCHED_POLL_INTERVAL
   :project: knit

sched_flux.sh
-------------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_sched_flux_cancel
   :project: knit

.. doxygenfunction:: _knit_sched_flux_directives
   :project: knit

.. doxygenfunction:: _knit_sched_flux_hostfile
   :project: knit

.. doxygenfunction:: _knit_sched_flux_parse_jobid
   :project: knit

.. doxygenfunction:: _knit_sched_flux_submit
   :project: knit

.. doxygenfunction:: _knit_sched_flux_submit_cmdline
   :project: knit

.. doxygenfunction:: _knit_sched_flux_wait
   :project: knit

.. doxygenfunction:: _knit_sched_flux_walltime_fsd
   :project: knit

sched_local.sh
--------------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_sched_local_cancel
   :project: knit

.. doxygenfunction:: _knit_sched_local_directives
   :project: knit

.. doxygenfunction:: _knit_sched_local_hostfile
   :project: knit

.. doxygenfunction:: _knit_sched_local_submit
   :project: knit

.. doxygenfunction:: _knit_sched_local_submit_cmdline
   :project: knit

.. doxygenfunction:: _knit_sched_local_wait
   :project: knit

sched_none.sh
-------------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_sched_none_cancel
   :project: knit

.. doxygenfunction:: _knit_sched_none_directives
   :project: knit

.. doxygenfunction:: _knit_sched_none_hostfile
   :project: knit

.. doxygenfunction:: _knit_sched_none_submit
   :project: knit

.. doxygenfunction:: _knit_sched_none_submit_cmdline
   :project: knit

.. doxygenfunction:: _knit_sched_none_wait
   :project: knit

sched_pbs.sh
------------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_sched_pbs_cancel
   :project: knit

.. doxygenfunction:: _knit_sched_pbs_directives
   :project: knit

.. doxygenfunction:: _knit_sched_pbs_hostfile
   :project: knit

.. doxygenfunction:: _knit_sched_pbs_parse_jobid
   :project: knit

.. doxygenfunction:: _knit_sched_pbs_submit
   :project: knit

.. doxygenfunction:: _knit_sched_pbs_submit_cmdline
   :project: knit

.. doxygenfunction:: _knit_sched_pbs_wait
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_SCHED_PBS_REGISTER_GRACE_POLLS
   :project: knit

sched_slurm.sh
--------------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_sched_slurm_cancel
   :project: knit

.. doxygenfunction:: _knit_sched_slurm_directives
   :project: knit

.. doxygenfunction:: _knit_sched_slurm_hostfile
   :project: knit

.. doxygenfunction:: _knit_sched_slurm_parse_jobid
   :project: knit

.. doxygenfunction:: _knit_sched_slurm_submit
   :project: knit

.. doxygenfunction:: _knit_sched_slurm_submit_cmdline
   :project: knit

.. doxygenfunction:: _knit_sched_slurm_wait
   :project: knit

set.sh
------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_set_add
   :project: knit

.. doxygenfunction:: _knit_set_array
   :project: knit

.. doxygenfunction:: _knit_set_exists
   :project: knit

.. doxygenfunction:: _knit_set_find
   :project: knit

.. doxygenfunction:: _knit_set_iter
   :project: knit

.. doxygenfunction:: _knit_set_new
   :project: knit

.. doxygenfunction:: _knit_set_remove
   :project: knit

setup.sh
--------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_default_setup
   :project: knit

.. doxygenfunction:: _knit_default_setup_path
   :project: knit

.. doxygenfunction:: _knit_experiment_root
   :project: knit

.. doxygenfunction:: _knit_has_user_setup
   :project: knit

.. doxygenfunction:: _knit_highlight_if_no_user_setup
   :project: knit

.. doxygenfunction:: _knit_job_root
   :project: knit

.. doxygenfunction:: _knit_resolve_experiment_path
   :project: knit

.. doxygenfunction:: _knit_setup
   :project: knit

.. doxygenfunction:: _knit_setup_after_cb
   :project: knit

.. doxygenfunction:: _knit_setup_before_cb
   :project: knit

.. doxygenfunction:: _knit_setup_check_type
   :project: knit

.. doxygenfunction:: _knit_setup_default_after_cb
   :project: knit

.. doxygenfunction:: _knit_setup_dep_after_cb
   :project: knit

.. doxygenfunction:: _knit_setup_dep_before_cb
   :project: knit

.. doxygenfunction:: _knit_setup_dep_resolve_path
   :project: knit

.. doxygenfunction:: _knit_setup_name_to_path
   :project: knit

.. doxygenfunction:: _knit_setup_provides_launcher_after_cb
   :project: knit

.. doxygenfunction:: _knit_setup_record_used_by_edge
   :project: knit

.. doxygenfunction:: _knit_setup_require_body
   :project: knit

.. doxygenfunction:: _knit_setup_root
   :project: knit

.. doxygenfunction:: _knit_setup_source_platform
   :project: knit

.. doxygenfunction:: _knit_setup_spack_env_after_cb
   :project: knit

.. doxygenfunction:: _knit_setup_spack_env_before_cb
   :project: knit

.. doxygenfunction:: _knit_setup_validate_var
   :project: knit

.. doxygenfunction:: _knit_setup_write_activate_header
   :project: knit

.. doxygenfunction:: _knit_stdin_is_terminal
   :project: knit

.. doxygenfunction:: _knit_validate_instance_name
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_SETUPS
   :project: knit

.. doxygenvariable:: _KNIT_SETUP_ACTIVATE_LINES
   :project: knit

shorthand.sh
------------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_shorthand_find_function
   :project: knit

.. doxygenfunction:: _knit_shorthand_generate
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_SHORTHAND_EXTRACTOR
   :project: knit

.. doxygenvariable:: _KNIT_SHORTHAND_PASSTHROUGH
   :project: knit

skills.sh
---------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_skills_download
   :project: knit

.. doxygenfunction:: _knit_skills_install
   :project: knit

.. doxygenfunction:: _knit_skills_link_claude
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_SKILLS_DEFAULT_REF
   :project: knit

.. doxygenvariable:: _KNIT_SKILLS_REPO
   :project: knit

spack.sh
--------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_bootstrap_need_spack
   :project: knit

.. doxygenfunction:: _knit_bootstrap_spack
   :project: knit

.. doxygenfunction:: _knit_bootstrap_spack_env_built
   :project: knit

.. doxygenfunction:: _knit_bootstrap_update_spack
   :project: knit

.. doxygenfunction:: _knit_spack
   :project: knit

.. doxygenfunction:: _knit_spack_download
   :project: knit

.. doxygenfunction:: _knit_spack_ensure_provisioned
   :project: knit

.. doxygenfunction:: _knit_spack_env_install
   :project: knit

.. doxygenfunction:: _knit_spack_exec
   :project: knit

.. doxygenfunction:: _knit_spack_framed_run
   :project: knit

.. doxygenfunction:: _knit_spack_github_api
   :project: knit

.. doxygenfunction:: _knit_spack_install
   :project: knit

.. doxygenfunction:: _knit_spack_latest_release
   :project: knit

.. doxygenfunction:: _knit_spack_resolve_commit
   :project: knit

.. doxygenfunction:: _knit_spack_write_repos_yaml
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_SPACK_ENV_SOURCED
   :project: knit

.. doxygenvariable:: _KNIT_SPACK_PACKAGES_ROOT
   :project: knit

.. doxygenvariable:: _KNIT_SPACK_REQUIRED
   :project: knit

.. doxygenvariable:: _KNIT_SPACK_ROOT
   :project: knit

sqlite.sh
---------

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_DATABASE
   :project: knit

.. doxygenvariable:: _KNIT_SQLITE_EXE
   :project: knit

.. doxygenvariable:: _KNIT_SQLITE_SOURCE_NAME
   :project: knit

.. doxygenvariable:: _KNIT_SQLITE_SOURCE_URL
   :project: knit

str.sh
------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_str_hyphens_to_underscores
   :project: knit

.. doxygenfunction:: _knit_str_render_cmd
   :project: knit

.. doxygenfunction:: _knit_str_underscores_to_hyphens
   :project: knit

types.sh
--------

Functions
~~~~~~~~~

.. doxygenfunction:: _knit_type_check_date
   :project: knit

.. doxygenfunction:: _knit_type_check_time
   :project: knit

.. doxygenfunction:: _knit_type_is_checksummable
   :project: knit

.. doxygenfunction:: _knit_type_resolve_alias
   :project: knit

.. doxygenfunction:: _knit_type_to_sqlite
   :project: knit

Variables
~~~~~~~~~

.. doxygenvariable:: _KNIT_BUILTIN_ENUMS
   :project: knit

.. doxygenvariable:: _KNIT_BUILTIN_TYPES
   :project: knit

.. doxygenvariable:: _KNIT_ENUMS
   :project: knit

.. doxygenvariable:: _KNIT_LAST_ENUM
   :project: knit

.. doxygenvariable:: _KNIT_TYPE_ALIASES
   :project: knit
