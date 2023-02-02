```
Flat's package manager

USAGE:
    airship <COMMAND> [OPTIONS]

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
    --debug, -d                        Print the command used to compile the package to stdout and exit
    --sync, -s                         Run the compilation synchronously
    --no-replace-log-line              Do not replace the logging info output after each line
    --quiet, -q                        Do not print Airship log messages
    --flatc-runtime                    Specify the Flat compiler runtime
```

--------------------------------------------------------------------------------

`airship setup`

```
Setup the Airship CLI

USAGE:
    airship setup [OPTIONS]

OPTIONS:
    --uninstall    Uninstall the Airship CLI package
    --reinstall    Reinstall the Airship CLI package
```

--------------------------------------------------------------------------------

`airship setup --uninstall`

```
Uninstall the Airship CLI package

USAGE:
    airship setup --uninstall
```

--------------------------------------------------------------------------------

`airship setup --reinstall`

```
Reinstall the Airship CLI package

USAGE:
    airship setup --reinstall
```

--------------------------------------------------------------------------------

`airship install`

```
Install a Flat package

USAGE:
    airship install [OPTIONS]

OPTIONS:
    --link    Link the Flat package to the location in C:/Users/Brade/.flat/packages
```

--------------------------------------------------------------------------------

`airship install --link`

```
Link the Flat package to the location in C:/Users/Brade/.flat/packages

USAGE:
    airship install --link
```

--------------------------------------------------------------------------------

`airship get`

```
Install the specified dependency

USAGE:
    airship get
```

--------------------------------------------------------------------------------

`airship uninstall`

```
Uninstall a Flat package

USAGE:
    airship uninstall
```

--------------------------------------------------------------------------------

`airship reinstall`

```
Reinstall a Flat package

USAGE:
    airship reinstall
```

--------------------------------------------------------------------------------

`airship update`

```
Update a Flat package's dependencies

USAGE:
    airship update
```

--------------------------------------------------------------------------------

`airship clean`

```
Clean a Flat package's out directory

USAGE:
    airship clean
```

--------------------------------------------------------------------------------

`airship run`

```
Run a script defined in a flat.json

USAGE:
    airship run
```

--------------------------------------------------------------------------------

`airship init`

```
Initialize a new Flat package, guided by a CLI prompt

USAGE:
    airship init
```

--------------------------------------------------------------------------------

`airship create`

```
Create Flat package scaffoldings

USAGE:
    airship create
```

--------------------------------------------------------------------------------

`airship bin`

```
Generate a Flat package binary file

USAGE:
    airship bin
```

--------------------------------------------------------------------------------

`airship add`

```
Add a Flat package as a dependency

USAGE:
    airship add
```

--------------------------------------------------------------------------------

`airship remove`

```
Remove a Flat package from the dependecies

USAGE:
    airship remove
```

--------------------------------------------------------------------------------

`airship help`

```
Print help information

USAGE:
    airship help [OPTIONS]

OPTIONS:
    --all    Print all the help information recursively for a command or option
```

--------------------------------------------------------------------------------

`airship help --all`

```
Print all the help information recursively for a command or option

USAGE:
    airship help --all
```

--------------------------------------------------------------------------------

`airship --version`

```
Print version info and exit

USAGE:
    airship --version
```

--------------------------------------------------------------------------------

`airship --target`

```
Specify the target language to compile the package to

USAGE:
    airship --target
```

--------------------------------------------------------------------------------

`airship --target-runtime`

```
Specify the target runtime the binary will build for

USAGE:
    airship --target-runtime
```

--------------------------------------------------------------------------------

`airship --file`

```
Specify an explicit flat.json file to reference when running the Airship commands

USAGE:
    airship --file
```

--------------------------------------------------------------------------------

`airship --debug`

```
Print the command used to compile the package to stdout and exit

USAGE:
    airship --debug
```

--------------------------------------------------------------------------------

`airship --sync`

```
Run the compilation synchronously

USAGE:
    airship --sync
```

--------------------------------------------------------------------------------

`airship --no-replace-log-line`

```
Do not replace the logging info output after each line

USAGE:
    airship --no-replace-log-line
```

--------------------------------------------------------------------------------

`airship --quiet`

```
Do not print Airship log messages

USAGE:
    airship --quiet
```

--------------------------------------------------------------------------------

`airship --flatc-runtime`

```
Specify the Flat compiler runtime

USAGE:
    airship --flatc-runtime
```