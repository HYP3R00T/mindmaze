---
title: Introduction to Linux Command and Shell Scripting
link: https://www.coursera.org/learn/hands-on-introduction-to-linux-commands-and-shell-scripting
series: IBM DevOps and Software Engineering Professional Certificate
platform: Coursera
tags:
  - course
  - devops
  - linux
  - shell_scripting
certification_link: 
completion_date:
---

- [Introduction to Linux Command and Shell Scripting](https://www.coursera.org/learn/hands-on-introduction-to-linux-commands-and-shell-scripting)
- [IBM DevOps and Software Engineering Professional Certificate](https://www.coursera.org/professional-certificates/devops-and-software-engineering)
- [Certificate]()

---

# Title

## Week 1

### Summary & Highlights

- In the 1980s, GNU was developed at MIT. GNU stands for “GNU’s not Unix” and was made as a free, open source set of the existing Unix system tools. And in 1991, Linus Torvalds developed a free, open source version of the Unix kernel called Linux.  
- Linux is widely used today in mobile devices, desktops, supercomputers, data centers, and cloud servers.
- Linux distributions (also known as distros) differ by their UIs, shell applications, and how the OS is supported and built.
- The design of a distro is catered toward its specific audience and/or use case. Popular Linux distributions include Red Hat Enterprise Linux (RHEL), Debian, Ubuntu, SUSE (SLES, SLED, OpenSuse), Fedora, Mint, and Arch.
- The Linux system consists of five key layers: the UI, application, OS, kernel, and hardware. The user interface enables users to interact with applications. Applications enable users to perform tasks within the system. The operating system runs on top of the kernel and is vital for system health and stability, and the kernel is the lowest-level software that enables applications to interact with hardware. Hardware includes all the physical or electronic components of your PC.
- The Linux filesystem is a tree-like structure consisting of all directories and files on the system.
- A Linux shell is an OS-level application that you can use to enter commands. You use a terminal to send commands to the shell, and you can use the `cd` command to navigate around your Linux filesystem.
- You can use a variety of command-line or GUI-based text editors such as GNU nano, vim, vi, and gedit.
- .deb and .rpm are distinct file types used by package mangers in Linux operating systems.
- You can use GUI-based and command-line package managers to update and install software on Linux systems.

## Week 2

### Common Linux Shell Commands

- Getting information
	- whoami
	- id
	- uname
	- ps
	- top
	- df
	- man
	- date
- Working with files
	- cp
	- mv
	- rm
	- touch
	- chmod
	- wc
	- grep
- Navigating & working with directories
	- ls
	- find
	- pwd
	- mkdir
	- cd
	- rmdir
- Printing file & string contents
	- cat
	- more
	- head
	- tail
	- echo
- Wrangling text files
	- sort
	- uniq
	- grep
	- cut
	- paste
- Compression & archiving
	- tar
	- zip
	- unzip
- Networking 
	- hostname
	- ping
	- ifconfig
	- curl
	- wget

### Module Summary & Highlights

- A shell is an interactive user interface. You use shell commands to navigate and work with files and directories.
- The `curl` and `wget` commands display and download files from URLs, and the`cat` and `tail`commands display file contents.
- You can get user information with the `whoami` and `id`commands, and get operating system information using the `uname` command. You can check system disk usage using the `df` command and monitor processes and resource usage with `ps` and `top`.Print string or variable value using `echo`,print and extract information about the date with the `date` command, and read the manual for any command using `man`.
- `ls` lists all files and directories within a specified directory tree and `cd` navigates between directories. The `find` command finds files in your directories.
- Relative paths are relative to your current working directory, while absolute paths stand independently
- You can create files and directories with the `touch` and `mkdir` commands, delete them with `rm` and `rmdir`, and copy and move them `cp` and `mv`.
- The `cat`, `more`, `head`, and `tail` commands allow you to sort and view file contents or view only a certain number of lines. Determine line, word, and character counts with `wc`.
- You can use `sort` to view the lines of a file alphanumerically and `uniq` to remove repeated lines from your view. `grep` gets the lines of a file that match your desired criteria, and `cut` extracts slices and fields from lines. You can merge lines from different files using `paste`.
- `hostname` and `ifconfig` allow you to view the network configuration. You can test a network connection using `ping` and send and receive data using `curl` and `wget`.
- Compression preserves storage space, speeds data transfer, and reduces system load.
- `zip` compresses files and folders prior to archiving them. `tar` archives and compresses files and directories into a tarball. `unzip` unpacks and decompresses a zipped archive, and `tar` can also decompress and unpack a tar.gz archive.

## Week 3

### Shell Scripting

- Shebang
	- `#! interpreter [args]`
- Shell variable
	- `sample_var = some_value`, then `echo $sample_var`
	- `read another_var`, then `echo $another_var` [This will read user input]
- Filters, Pipes, & Variables
	- `|` chain filters commands
	- `set` list all shell variables
	- `var_name=value` define shell variables
	- `unset var_name` unset a variable
	- `export var_name` to create environment variable
- Metacharacters
	- `#` - precedes a comment
	- `;` - command separator
	- `*` - filename expansion wildcard
	- `?` - single character wildcard in filename expansion
- Quoting
	- `\` - escape unique character interpretation
	- `" "` - interpret literally, but evaluate metacharacters
	- `' '` - interpret literally
- I/O redirection
	- `>` - redirect output to the file
	- `>>` - append output to the file
	- `2>` - Redirect standard error to file
	- `2>>` - Append standard error to file
	- `<` - Redirect file contents to standard input
- Command substitution
	- `$(command)` or `` `command` ``
