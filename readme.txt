$ ./hostess --help
Usage:
    hostess [OPTIONS] SUBCOMMAND [ARGS] ...

Parameters:
    SUBCOMMAND                    subcommand name
    [ARGS] ...                    subcommand arguments

Subcommands:
    set                           LOCATION    Change to a new location
    add                           LOCATION    Create new location
    del                           LOCATION    Delete a location
    list                          (LOCATION)    List locations or all entries for a specific location
    block                         LOCATION HOSTS ...  Block all hosts for a specific location
    unblock                       LOCATION HOSTS ...  Unblock all hosts for a specific location
    redirect                      LOCATION HOST IP  Redirect host for a specific location
    blacklist                     HOST      Blacklist a host from all locations
    whitelist                     HOST      Remove host from blacklist
    reload                              Reload the current location
    config                              Generate basic config

Options:
    version, --version            Show version information
    --help                        print help

