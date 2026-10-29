# Linux Fundamentals Part 1

> Personal study notes from TryHackMe / Cybersecurity 101.

# 1. WHAT IS LINUX

Linux is an open-source operating system that manages computer hardware, memory, files, and applications.It is similar to Windows, but it is widely used in servers, cloud computing, and cybersecurity.Examples: Ubuntu, Kali Linux.

# 2. THE TERMINAL

A terminal is a program where you type commands to interact with the operating system instead of clicking icons. The shell reads and executes those commands. It is especially useful for managing Linux servers.

# 3. FIRST COMMADS

| command | what it does |
| --- | --- |
| echo hello | prints text back to the screen |
| whoami | show which user you are logged in as |

# 4. MOVING AROUND THE FILESYSTEM

| commands | what it does | analogy |
| --- | --- | --- |
| ls | list files and folders | look inside a room |
| cd folder | change directory(go into a folder) | walking into a another room |
| cd.. | go backup one folder | stepping back out |
| pwd | print working directory (where i am?) | “you are here” on the map |
| cat file | prints files contents on screen | reading a note |
| mkdir name | make a new folder |  |

# 5. SEARCH FOR THE THINGS

- find = searches for file by name: find -name password.txt

- wildcard means *  “ anything ”: find -name *.txt   ;find every files ending in txt

- grep searches insides files for text: grep “password” file .txt

# 6. SHELL OPERATORS

symbols tat change how commands behave

| operator | meaning | example |
| --- | --- | --- |
| & | run the command in the bg | command & |
| && | run the second command only if the first succeeds | command&& cmd 2 |
| > | send output into a file, overwriting it | echo hi > file .txt |
| >> | send output into a file, adding to the end | echo hi >> file txt |

\>it wipes the files old content

# quick recap

- see: ls, pwd, cat

- move: cd

- find: find, grep

- combine and redirect: &,&&,>,>>
