# through the process of learning - bash

Collection of scripts and resources gathered through the process of 
learning [bash](http://en.wikipedia.org/wiki/bash_\(unix_shell\)).

**This work is by no means complete and is written from a bash beginner's
perspective**. It assumes the viewer is familiar with programming and is 
comfortable in a terminal window but has little to no bash experience.


# Examples

Examples are organized by tool or concept. Scripts are written and known
to work using GNU bash version 3.2.48 _(default OSX 10.6 installation)_. 

**Topics** _(order alphabetically)_

* [awk](./examples/awk)
* [basic](./examples/basic)
* [break](./examples/break)
* [case](./examples/case)
* [continue](./examples/continue)
* [expansion](./examples/expansion)
* [expressions](./examples/expressions)
* [for](./examples/for)
* [pipes](./examples/pipes)
* [printf](./examples/printf)
* [read](./examples/read)
* [redirection](./examples/redirection)
* [sed](./examples/sed)
* [strings](./examples/strings)
* [tests](./examples/tests)
* [until](./examples/until)
* [while](./examples/while)

[See all examples](./examples/)

Best method of using the examples is to open the file to
view the source comments followed by running the file in terminal to see the results.
Some examples are explained in comments and others in the output so check both.

# Resources

[Links, Books, & everthing else](./RESOURCES.md)


# Tools

### [bash-bp](./bin/bash-bp) - BASH Executable Boilerplate

A helper for creating a new (executable) bash file.

Usage:

    bash-bp -h

Example:

    $ bash-bp -f mytool

Check to make sure the file was created:

    $ cat mytool
    
      #!/bin/bash
      
      # code goes here

Make sure it's executable:

    $ test -x mytool && echo true || echo false
    
    true


# License

![Creative Commons License](http://i.creativecommons.org/l/by-sa/3.0/88x31.png)

This work is licensed under a [Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/)
