.. _hasura_metadata_reload:

Hasura CLI: hasura metadata reload
----------------------------------

Reload Hasura GraphQL Engine metadata on the database

Synopsis
~~~~~~~~


Reload Hasura GraphQL Engine metadata on the database

::

  hasura metadata reload [flags]

Examples
~~~~~~~~

::

    # Reload all the metadata information from database:
    hasura metadata reload

Options
~~~~~~~

::

      --access-key string   access key for Hasura GraphQL Engine
      --endpoint string     http(s) endpoint for Hasura GraphQL Engine
  -h, --help                help for reload

Options inherited from parent commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

      --project string   hasura project directory where the commands should be executed. (default: current directory)

SEE ALSO
~~~~~~~~

* :ref:`hasura metadata <hasura_metadata>` 	 - Manage Hasura GraphQL Engine metadata saved in the database

*Auto generated by spf13/cobra*
