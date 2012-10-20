# through the process of learning - bash

Collection of scripts and resources gathered through the process of 
learning [bash](http://en.wikipedia.org/wiki/bash_\(Unix_shell\)).

**This work is by no means complete and is written from a bash beginner's
perspective**. It assumes the viewer is familiar with programming and is 
comfortable in a terminal window but has little to no bash experience.


## Examples

Examples are organized by tool or concept. Scripts are written and known
to work using GNU bash version 3.2.48 _(default OSX 10.6 installation)_. 

**Topics** _(ordered alphabetically)_

* [awk](tpl-bash/tree/master/examples/awk)
* [basic](tpl-bash/tree/master/examples/basic)
* [break](tpl-bash/tree/master/examples/break)
* [case](tpl-bash/tree/master/examples/case)
* [continue](tpl-bash/tree/master/examples/continue)
* [expansion](tpl-bash/tree/master/examples/expansion)
* [expressions](tpl-bash/tree/master/examples/expressions)
* [for](tpl-bash/tree/master/examples/for)
* [pipes](tpl-bash/tree/master/examples/pipes)
* [printf](tpl-bash/tree/master/examples/printf)
* [read](tpl-bash/tree/master/examples/read)
* [redirection](tpl-bash/tree/master/examples/redirection)
* [sed](tpl-bash/tree/master/examples/sed)
* [strings](tpl-bash/tree/master/examples/strings)
* [tests](tpl-bash/tree/master/examples/tests)
* [until](tpl-bash/tree/master/examples/until)
* [while](tpl-bash/tree/master/examples/while)

[See all examples](tpl-bash/tree/master/examples/)

Best method of using the examples is to open the file to
view the source comments followed by running the file in terminal to see the results.
Some examples are explained in comments and others in the output so check both.

## Resources

[Links, Books, & everthing else](tpl-bash/tree/master/RESOURCES.md)


## Tools

### [bash-bp](tpl-bash/tree/master/bin/bash-bp) - BASH Executable Boilerplate

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
