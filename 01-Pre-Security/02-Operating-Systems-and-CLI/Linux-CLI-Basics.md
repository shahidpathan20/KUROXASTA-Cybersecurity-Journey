# Linux CLI Basics

## What is the CLI?
A **command-line interface (CLI)** lets you interact with a computer by typing commands instead of clicking through menus. A terminal is an application where you enter commands into a shell.

## Navigation commands
| Command | Purpose |
|---|---|
| `pwd` | Prints the current working directory. |
| `ls` | Lists files and directories. |
| `cd Documents` | Changes into the Documents directory if it exists there. |
| `cd ..` | Moves up one directory. |
| `cd ~` | Moves to the current user's home directory. |

## Finding and reading files
- `find / -name "file.txt"` searches from the filesystem root for a matching filename. Permission errors may appear.
- `cat file.txt` displays a file's contents. Read only files you are authorized to access.

## System information
| Command | Purpose |
|---|---|
| `whoami` | Shows the current user. |
| `uname -a` | Displays kernel and system information. |
| `df -h` | Shows disk-space usage in human-readable units. |

**Quick revision:** pwd = current location; ls = list files; cd = change directory; find = search; cat = read; whoami = current user; uname -a = system details; df -h = disk usage.

[Back to Operating Systems and CLI](README.md)