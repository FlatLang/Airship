```
Flat's package manager

USAGE:
    airship {COMMAND} [OPTIONS]

COMMANDS:
    setup         Setup the Airship CLI
    install, i    Install a Flat package
    get           Install the specified dependency
    uninstall     Uninstall a Flat package
    reinstall     Reinstall a Flat package
    update, u     Update a Flat package's dependencies
    clean, c      Clean a Flat package's out directory
    run, r        Run a script defined in a flat.json
    init          Initialize a new Flat package, guided by a CLI prompt
    create        Create Flat package scaffoldings
    bin           Generate a Flat package binary file
    add           Add a Flat package as a dependency
    remove        Remove a Flat package from the dependecies
    help, ?       Print help information

OPTIONS:
    --version                          Print version info and exit
    --target, -t                       Specify the target language to compile the package to
    --target-runtime, --runtime, -r    Specify the target runtime the binary will build for
    --file, -f                         Specify an explicit flat.json file to reference when running the Airship commands
    --link                             Link the Flat package to the location in C:/Users/Brade/.flat/packages
    --debug, -d                        Print the command used to compile the package to stdout and exit
    --sync, -s                         Run the compilation synchronously
    --no-replace-log-line              Do not replace the logging info output after each line
    --quiet, -q                        Do not print Airship log messages
    --uninstall                        Uninstall the Airship CLI package
    --reinstall                        Reinstall the Airship CLI package
    --flatc-runtime                    Specify the Flat compiler runtime
```