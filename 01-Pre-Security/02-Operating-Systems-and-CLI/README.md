# Operating Systems and CLI

## 1. Operating System Basics
An **operating system (OS)** manages a computer's hardware and software resources. It acts as an interface between users, applications, and hardware.

An OS manages CPU time, memory, storage, devices, files, folders, and security features. Common operating systems include Windows, Linux, macOS, and Android.

**Summary:** an OS coordinates hardware and software so applications can run and users can interact with a computer.

## 2. Windows Basics
Windows is an operating system with a graphical user interface (GUI).

- **Desktop:** main workspace with icons and shortcuts.
- **Start menu:** access to apps, settings, and files.
- **Taskbar:** shows running and pinned apps.
- **File Explorer:** manages files and folders.
- **Task Manager:** displays processes and resource usage.
- **Settings / Control Panel:** configure system options.
- **Microsoft Defender:** built-in malware protection.
- **Windows Firewall:** helps block unauthorized network connections.
- **Windows Update:** installs updates and security patches.

## 3. Linux CLI Basics

### What is the CLI?
A **command-line interface (CLI)** lets you interact with a computer by typing commands instead of clicking through menus. A terminal is an application where you enter commands into a shell.

CLI is important because many Linux servers and cybersecurity tools are managed from terminals, and commands can help automate repetitive work.

### Navigation commands
| Command | Purpose |
|---|---|
| pwd | Prints the current working directory. |
| ls | Lists files and directories. |
| cd Documents | Changes into the Documents directory if it exists there. |
| cd .. | Moves up one directory. |
| cd ~ | Moves to the current user's home directory. |

### Finding and reading files
- **find / -name "file.txt"** searches from the filesystem root for a matching filename. Permission errors may appear.
- **cat file.txt** displays the contents of a file. Read only files you are authorized to access.

### System information
| Command | Purpose |
|---|---|
| whoami | Shows the current user. |
| uname -a | Displays kernel and system information. |
| df -h | Shows disk-space usage in human-readable units. |

**Quick revision:** pwd = current location; ls = list files; cd = change directory; find = search; cat = read; whoami = current user; uname -a = system details; df -h = disk usage.

## 4. Windows CLI Basics
The current Notion page for this topic contains only the heading “CLI ()” and no detailed lesson text. This is recorded honestly rather than inventing a full lesson.

Windows provides command-line environments such as **Command Prompt** and **PowerShell**. Their commands and syntax can differ, so always identify which shell you are using before running a command.
