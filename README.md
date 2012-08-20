# Erlang plugin
Erlang language support for IntelliJ Platform (e.g. IntelliJ IDEA).
## WORK IN PROGRESS
You can manually set up the latest version of plugin from the [Erlang.zip](https://github.com/ignatov/intellij-erlang/raw/master/bin/Erlang.zip) file.

## Contributing
If you want to help but doesn't know how, you may check out issues [for collaboration](https://github.com/ignatov/intellij-erlang/issues?labels=for+collaboration&state=open).

## Compilation and running
The recent build supports compiling and running Erlang projects.

You need to specify module name, function name and input parameters in run configuration setting. Enjoy!

![Compilation and run](https://github.com/ignatov/intellij-erlang/raw/master/images/hello-run-configuration.png)

## Change log

### Version 0.2.5:
* Compilation and run
* Resolve, completion, rename and find usages for macroses

### Version 0.2:
* Erlang SDK
* Autocompletion for BIFs
* Creating project from scratch or existing sources
* Color setting page
* New inspections: unused functions and variables, duplicated functions
* Quick fix for incorrect module name
* 'New File From Template' action
* Bugfixes

### Version 0.1:
* Syntax and errors highlighting
* References resolving
* Code completion for functions, records and variables
* Keyword code completion
* Rename refactoring for modules, functions, records and variables
* Safe delete refactoring
* Structure view
* Find usages
* Code commenting/uncommenting
* Brace matching