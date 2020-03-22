# linux-command-line

Shell and Terminal
The shell is the command line interpreter, it takes the commands that you enter and sends them to the operating system to be executed. The shell is what actually handles the commands.

The Terminal was a physical device that connects to a computer, usually
over serial cable or modem. Nowadays, when someone says a Terminal, he really means a Terminal emulator. Software that imitates the physical device that was once called a Terminal.

The Terminal is a GUI (Graphical User Interface) to the shell. In other
words, we access the shell through our terminal.

Basic Commands
Commands are case sensitive, almost all commands are in lowercase.

    - date = current date
    -      cal = current month calendar
        flags:
        -y = current year calendar
        year number, ex: cal 2000
        month number year number, ex: cal 9 2000
        -3, ex: cal -3, displays the previous, current and upcoming month calendars
        - clear = clears terminal
        - exit = exits current terminal session

The Linux file system
The file system has a tree like structure, also referred to as
the Directory tree. A directory is a location that stores multiple files, aka folder.

The Directory Tree
Each directory and/or file has one parent.

The first directory (top most) in our directory tree is called the root directory and is represented by a forward slash /

The root directory contains files and subdirectories, which contain more files and subdirectories and so on.

Common Directories
/ = root directory, has no parent
/etc = contains system configuration files
/bin = stands for binary, contains the commands and utilities used on a daily basis (All users have access to it)
/sbin = contains programs that performs vital system tasks (Network management, Disk
partitioning). Only the superuser has access to these programs.
/home = each user is given a home directory to store their files.
/opt = stands for optional, contains optional software not installed by default.
/tmp = stands for temporary, contains temporary files created by various programs. Generally cleared on reboot.
/var = stands for variable, contains variable data.

Absolute and relative paths
An absolute path begins with the root directory and follows the directory tree branch by branch until the path to the desired directory or file is completed.
A relative path starts from the current working directory. You can refere to it by using ./ or a directory or filename present a the current folder.

Navigating the File system
(1) The root directory is represented as /
(2) The home directory is represented as ~
(3) The current directory is represented as .
(4) The parent directory is represeted as ..
(5) The previous directory is represented as ­-

Navigation commands
pwd = stands for print working directory, prints the absolute path name of your
current working directory.
cd = stands for change directory
cd directoryName = Changes to the inputed directory name
cd / = Changes to your root directory
cd ~ = Changes to your home directory
cd .. = Changes to your parent directory
cd ­- = Changes to your previous directory
ls = stands for list, lists all the files on the current working directory
