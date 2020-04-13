# Project BASH Command Line Arguments

This simple project is a relatively simple tool for processing
command line arguments in a BASH script.

For this implementation, each command line option is a single
letter, preceded by a dash.  Examples would be **-b** or **-p**.

For now, arguments cannot be combined.  That means you cannot
use an option **-bf**.  You will have to enter the **b** and **f**
options separately.

## Project Contents

There are two files in this project, **bash_clargs** containing
the command line processing functions and support, and **demo**,
a script showing how the utility can be used.

## Option Types Supported

Options may stand alone or precede a value.  Standalone options are
executed immediately, 

- **variable** sets a variable
- **flag** sets a flag
- **deferred function** calls a function with 
  of the option tag followed by the value to set for the option.

  

  ~~~sh
  yourprogram -n Bob
  ~~~
