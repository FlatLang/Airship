```
Flat's package manager

USAGE:
    airship <command> [options]

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
    airship setup [options]

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
    airship install <installationTarget> [--link]

ARGUMENTS:
    <installationTarget>    The package installation target

OPTIONS:
    --link    Link the Flat package to the location in $FLAT_HOME/packages
```

--------------------------------------------------------------------------------

`airship install <installationTarget>`

```
The package installation target

USAGE:
    airship install <installationTarget>
```

--------------------------------------------------------------------------------

`airship install --link`

```
Link the Flat package to the location in $FLAT_HOME/packages

USAGE:
    airship install --link
```

--------------------------------------------------------------------------------

`airship get`

```
Install the specified dependency

USAGE:
    airship get <dependency>

ARGUMENTS:
    <dependency>    The dependencies to get
```

--------------------------------------------------------------------------------

`airship get <dependency>`

```
The dependencies to get

USAGE:
    airship get <dependency>
```

--------------------------------------------------------------------------------

`airship uninstall`

```
Uninstall a Flat package

USAGE:
    airship uninstall <installationTarget> [--link]

ARGUMENTS:
    <installationTarget>    The installation target to uninstall

OPTIONS:
    --link    Uninstall a symbolic link of the Flat package from the location in $FLAT_HOME/packages
```

--------------------------------------------------------------------------------

`airship uninstall <installationTarget>`

```
The installation target to uninstall

USAGE:
    airship uninstall <installationTarget>
```

--------------------------------------------------------------------------------

`airship uninstall --link`

```
Uninstall a symbolic link of the Flat package from the location in $FLAT_HOME/packages

USAGE:
    airship uninstall --link
```

--------------------------------------------------------------------------------

`airship reinstall`

```
Reinstall a Flat package

USAGE:
    airship reinstall <installationTarget> [--link]

ARGUMENTS:
    <installationTarget>    The installation target to reinstall

OPTIONS:
    --link    Link the Flat package to the location in $FLAT_HOME/packages
```

--------------------------------------------------------------------------------

`airship reinstall <installationTarget>`

```
The installation target to reinstall

USAGE:
    airship reinstall <installationTarget>
```

--------------------------------------------------------------------------------

`airship reinstall --link`

```
Link the Flat package to the location in $FLAT_HOME/packages

USAGE:
    airship reinstall --link
```

--------------------------------------------------------------------------------

`airship update`

```
Update a Flat package's dependencies

USAGE:
    airship update <installationTarget>

ARGUMENTS:
    <installationTarget>    The installation target to update the dependencies for
```

--------------------------------------------------------------------------------

`airship update <installationTarget>`

```
The installation target to update the dependencies for

USAGE:
    airship update <installationTarget>
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
    airship run <script>

ARGUMENTS:
    <script>    The name of the script to run
```

--------------------------------------------------------------------------------

`airship run <script>`

```
The name of the script to run

USAGE:
    airship run <script>
```

--------------------------------------------------------------------------------

`airship init`

```
Initialize a new Flat package, guided by a CLI prompt

USAGE:
    airship init <packageName>

ARGUMENTS:
    <packageName>    The name of the package to initialize
```

--------------------------------------------------------------------------------

`airship init <packageName>`

```
The name of the package to initialize

USAGE:
    airship init <packageName>
```

--------------------------------------------------------------------------------

`airship create`

```
Create Flat package scaffoldings

USAGE:
    airship create <arguments>

ARGUMENTS:
    <pipeline>       The type of pipeline to create
    <pipelineArg>    An argument to pass to the pipeline creation
```

--------------------------------------------------------------------------------

`airship create <pipeline>`

```
The type of pipeline to create

USAGE:
    airship create <pipeline>
```

--------------------------------------------------------------------------------

`airship create <pipelineArg>`

```
An argument to pass to the pipeline creation

USAGE:
    airship create <pipelineArg>
```

--------------------------------------------------------------------------------

`airship bin`

```
Generate a Flat package binary file

USAGE:
    airship bin <binary>

ARGUMENTS:
    <binary>    The name of the binary to create
```

--------------------------------------------------------------------------------

`airship bin <binary>`

```
The name of the binary to create

USAGE:
    airship bin <binary>
```

--------------------------------------------------------------------------------

`airship add`

```
Add a Flat package as a dependency

USAGE:
    airship add <dependency>

ARGUMENTS:
    <dependency>    The dependency to add
```

--------------------------------------------------------------------------------

`airship add <dependency>`

```
The dependency to add

USAGE:
    airship add <dependency>
```

--------------------------------------------------------------------------------

`airship remove`

```
Remove a Flat package from the dependecies

USAGE:
    airship remove <dependency>

ARGUMENTS:
    <dependency>    The dependency to remove
```

--------------------------------------------------------------------------------

`airship remove <dependency>`

```
The dependency to remove

USAGE:
    airship remove <dependency>
```

--------------------------------------------------------------------------------

`airship help`

```
Print help information

USAGE:
    airship help <name> [--all]

ARGUMENTS:
    <name>    The name of the argument, command, or option to get help on

OPTIONS:
    --all    Print all the help information recursively for an argument, command, or option
```

--------------------------------------------------------------------------------

`airship help <name>`

```
The name of the argument, command, or option to get help on

USAGE:
    airship help <name>
```

--------------------------------------------------------------------------------

`airship help --all`

```
Print all the help information recursively for an argument, command, or option

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
    airship --target <target>

ARGUMENTS:
    <target>    The language to compile the package to
```

--------------------------------------------------------------------------------

`airship --target <target>`

```
The language to compile the package to

USAGE:
    airship --target <target>
```

--------------------------------------------------------------------------------

`airship --target-runtime`

```
Specify the target runtime the binary will build for

USAGE:
    airship --target-runtime <runtime>

ARGUMENTS:
    <runtime>    The language runtime to compile the package for
```

--------------------------------------------------------------------------------

`airship --target-runtime <runtime>`

```
The language runtime to compile the package for

USAGE:
    airship --target-runtime <runtime>
```

--------------------------------------------------------------------------------

`airship --file`

```
Specify an explicit flat.json file to reference when running the Airship commands

USAGE:
    airship --file <file>

ARGUMENTS:
    <file>    The flat.json file location to use
```

--------------------------------------------------------------------------------

`airship --file <file>`

```
The flat.json file location to use

USAGE:
    airship --file <file>
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
    airship --flatc-runtime <runtime>

ARGUMENTS:
    <runtime>    The flatc runtime to compile the package with
```

--------------------------------------------------------------------------------

`airship --flatc-runtime <runtime>`

```
The flatc runtime to compile the package with

USAGE:
    airship --flatc-runtime <runtime>
```