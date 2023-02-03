```
Flat's package manager

Usage:
    airship <command> [options]

Commands:
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

Options:
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

Usage:
    airship setup [options]

Options:
    --uninstall    Uninstall the Airship CLI package
    --reinstall    Reinstall the Airship CLI package
```

--------------------------------------------------------------------------------

`airship setup --uninstall`

```
Uninstall the Airship CLI package

Usage:
    airship setup --uninstall
```

--------------------------------------------------------------------------------

`airship setup --reinstall`

```
Reinstall the Airship CLI package

Usage:
    airship setup --reinstall
```

--------------------------------------------------------------------------------

`airship install`

```
Install a Flat package

Usage:
    airship install <installationTarget> [--link]

Arguments:
    <installationTarget>    The package installation target

Options:
    --link    Link the Flat package to the location in C:/Users/Brade/.flat/packages
```

--------------------------------------------------------------------------------

`airship install <installationTarget>`

```
The package installation target

Usage:
    airship install <installationTarget>
```

--------------------------------------------------------------------------------

`airship install --link`

```
Link the Flat package to the location in C:/Users/Brade/.flat/packages

Usage:
    airship install --link
```

--------------------------------------------------------------------------------

`airship get`

```
Install the specified dependency

Usage:
    airship get <dependency>

Arguments:
    <dependency>    The dependencies to get
```

--------------------------------------------------------------------------------

`airship get <dependency>`

```
The dependencies to get

Usage:
    airship get <dependency>
```

--------------------------------------------------------------------------------

`airship uninstall`

```
Uninstall a Flat package

Usage:
    airship uninstall <installationTarget>

Arguments:
    <installationTarget>    The installation target to uninstall
```

--------------------------------------------------------------------------------

`airship uninstall <installationTarget>`

```
The installation target to uninstall

Usage:
    airship uninstall <installationTarget>
```

--------------------------------------------------------------------------------

`airship reinstall`

```
Reinstall a Flat package

Usage:
    airship reinstall <installationTarget>

Arguments:
    <installationTarget>    The installation target to reinstall
```

--------------------------------------------------------------------------------

`airship reinstall <installationTarget>`

```
The installation target to reinstall

Usage:
    airship reinstall <installationTarget>
```

--------------------------------------------------------------------------------

`airship update`

```
Update a Flat package's dependencies

Usage:
    airship update <installationTarget>

Arguments:
    <installationTarget>    The installation target to update the dependencies for
```

--------------------------------------------------------------------------------

`airship update <installationTarget>`

```
The installation target to update the dependencies for

Usage:
    airship update <installationTarget>
```

--------------------------------------------------------------------------------

`airship clean`

```
Clean a Flat package's out directory

Usage:
    airship clean
```

--------------------------------------------------------------------------------

`airship run`

```
Run a script defined in a flat.json

Usage:
    airship run <script>

Arguments:
    <script>    The name of the script to run
```

--------------------------------------------------------------------------------

`airship run <script>`

```
The name of the script to run

Usage:
    airship run <script>
```

--------------------------------------------------------------------------------

`airship init`

```
Initialize a new Flat package, guided by a CLI prompt

Usage:
    airship init <packageName>

Arguments:
    <packageName>    The name of the package to initialize
```

--------------------------------------------------------------------------------

`airship init <packageName>`

```
The name of the package to initialize

Usage:
    airship init <packageName>
```

--------------------------------------------------------------------------------

`airship create`

```
Create Flat package scaffoldings

Usage:
    airship create <arguments>

Arguments:
    <pipeline>       The type of pipeline to create
    <pipelineArg>    An argument to pass to the pipeline creation
```

--------------------------------------------------------------------------------

`airship create <pipeline>`

```
The type of pipeline to create

Usage:
    airship create <pipeline>
```

--------------------------------------------------------------------------------

`airship create <pipelineArg>`

```
An argument to pass to the pipeline creation

Usage:
    airship create <pipelineArg>
```

--------------------------------------------------------------------------------

`airship bin`

```
Generate a Flat package binary file

Usage:
    airship bin <binary>

Arguments:
    <binary>    The name of the binary to create
```

--------------------------------------------------------------------------------

`airship bin <binary>`

```
The name of the binary to create

Usage:
    airship bin <binary>
```

--------------------------------------------------------------------------------

`airship add`

```
Add a Flat package as a dependency

Usage:
    airship add <dependency>

Arguments:
    <dependency>    The dependency to add
```

--------------------------------------------------------------------------------

`airship add <dependency>`

```
The dependency to add

Usage:
    airship add <dependency>
```

--------------------------------------------------------------------------------

`airship remove`

```
Remove a Flat package from the dependecies

Usage:
    airship remove <dependency>

Arguments:
    <dependency>    The dependency to remove
```

--------------------------------------------------------------------------------

`airship remove <dependency>`

```
The dependency to remove

Usage:
    airship remove <dependency>
```

--------------------------------------------------------------------------------

`airship help`

```
Print help information

Usage:
    airship help <name> [--all]

Arguments:
    <name>    The name of the argument, command, or option to get help on

Options:
    --all    Print all the help information recursively for an argument, command, or option
```

--------------------------------------------------------------------------------

`airship help <name>`

```
The name of the argument, command, or option to get help on

Usage:
    airship help <name>
```

--------------------------------------------------------------------------------

`airship help --all`

```
Print all the help information recursively for an argument, command, or option

Usage:
    airship help --all
```

--------------------------------------------------------------------------------

`airship --version`

```
Print version info and exit

Usage:
    airship --version
```

--------------------------------------------------------------------------------

`airship --target`

```
Specify the target language to compile the package to

Usage:
    airship --target <target>

Arguments:
    <target>    The language to compile the package to
```

--------------------------------------------------------------------------------

`airship --target <target>`

```
The language to compile the package to

Usage:
    airship --target <target>
```

--------------------------------------------------------------------------------

`airship --target-runtime`

```
Specify the target runtime the binary will build for

Usage:
    airship --target-runtime <runtime>

Arguments:
    <runtime>    The language runtime to compile the package for
```

--------------------------------------------------------------------------------

`airship --target-runtime <runtime>`

```
The language runtime to compile the package for

Usage:
    airship --target-runtime <runtime>
```

--------------------------------------------------------------------------------

`airship --file`

```
Specify an explicit flat.json file to reference when running the Airship commands

Usage:
    airship --file <file>

Arguments:
    <file>    The flat.json file location to use
```

--------------------------------------------------------------------------------

`airship --file <file>`

```
The flat.json file location to use

Usage:
    airship --file <file>
```

--------------------------------------------------------------------------------

`airship --debug`

```
Print the command used to compile the package to stdout and exit

Usage:
    airship --debug
```

--------------------------------------------------------------------------------

`airship --sync`

```
Run the compilation synchronously

Usage:
    airship --sync
```

--------------------------------------------------------------------------------

`airship --no-replace-log-line`

```
Do not replace the logging info output after each line

Usage:
    airship --no-replace-log-line
```

--------------------------------------------------------------------------------

`airship --quiet`

```
Do not print Airship log messages

Usage:
    airship --quiet
```

--------------------------------------------------------------------------------

`airship --flatc-runtime`

```
Specify the Flat compiler runtime

Usage:
    airship --flatc-runtime <runtime>

Arguments:
    <runtime>    The flatc runtime to compile the package with
```

--------------------------------------------------------------------------------

`airship --flatc-runtime <runtime>`

```
The flatc runtime to compile the package with

Usage:
    airship --flatc-runtime <runtime>
```