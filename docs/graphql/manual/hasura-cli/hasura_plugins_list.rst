.. meta::
   :description: Use hasura plugins list to list Hasura plugins on the Hasura CLI
   :keywords: hasura, docs, CLI, hasura plugins list

.. _hasura_plugins_list:

Hasura CLI: hasura plugins list
-------------------------------

List all Hasura plugins.

Synopsis
~~~~~~~~


List all Hasura plugins.

::

  hasura plugins list [flags]

Alias: ls

Examples
~~~~~~~~

::

    # List all hasura plugins
    hasura plugins list
   
    # The command also updates the plugin index that is cached locally
    # To avoid updating the index, use the following flag:
    hasura plugins list --dont-update-index

Options
~~~~~~~

::

      --dont-update-index   don't update the plugin index local cache, only show the list
  -h, --help                help for list

Options inherited from parent commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

      --envfile string      .env filename to load ENV vars from (default ".env")
      --log-level string    log level (DEBUG, INFO, WARN, ERROR, FATAL) (default "INFO")
      --no-color            do not colorize output (default: false)
      --project string      directory where commands are executed (default: current dir)
      --skip-update-check   skip automatic update check on command execution

SEE ALSO
~~~~~~~~

* :ref:`hasura plugins <hasura_plugins>` 	 - Manage hasura plugins

*Auto generated by spf13/cobra*
