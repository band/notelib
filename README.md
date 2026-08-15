# notelib  

A `zsh | bash` library for simple note-taking at the command-line.

## Install

Clone or download the `.zip` file of this folder and `source` the
library; i.e.:

``` shell
source notelib
```  

For help `notelib -h` or `notelib`  

```
NAME
  notelib - functions for command-line text or markdown note taking

SYNOPSIS
  n [notefile_name]	     Create a new note or Open an existing note; default name is a timestamp
	nlast			     Edit the most recent note
  nls [pattern]		     List notes matching name, or with no argument, list all
  notelib [-v|-V|--version]  Display release/version info
  notelib [-h|--help|help]   Display this help info

ENVIRONMENT
  NOTES		The notes directory. `~/text/notes` is the default if not set
  EDITOR	The editor app used to create and update notes
```  


