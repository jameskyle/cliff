=================
 Release History
=================

dev

  - Add trailing newlines after output from tablib-based formatters
    (JSON, YAML, and HTML). Contributed by Matt Joyce.

0.7

  - Clean up interactive mode flag settting.
  - Add support for Python 2.6, contributed by heavenshell.
  - Fix multi-word commands in interactive mode.

0.6

  - Pass the non-global argument list to :func:`initialize_app` to be
    used in initialization work.

0.5.1

  - Remove pinned version requirement for PrettyTable until the
    OpenStack clients catch up to the API change.

0.5

  - Asking for help about a command by prefix lists all matching
    commands.
  - Add formatters for HTML, JSON, and YAML.

0.4

  - Add shell formatter for single objects.
  - Add interactive mode.
  - Expand documentation.

0.3

  - Add ShowOne base class for commands that show details about single
    objects.
  - Fix a problem with Lister when there is no data to be printed.

0.2

  - Incorporate changes from dtroyer to replace use of optparse in App
    with argparse.
  - Added "help" subcommand to replace ``--help`` option handling in
    subcommands.

0.1

  - Initial public release.
  - Included App, CommandManager, Lister, csv and table formatters, a
    demo application, and basic documentation.
