This project focuses on building a shell terminal using the programming language C

The following are the list of commands that can be executed:
//ls- lists files and directories in current directory
//dir - lists files and directories in current directory
//history- list of all commands typed by the user
//move filepath
//move .. navigation to parent folder
//!1 to rerun the first command
//!2 to rerun the second command
//!n to rerun the nth command
//notepad <filename>- opens an existing notepad file from the current directory or else creates a new notepad file in the current directory
//exit


1. **Strings:** Strings are used to store and manipulate textual data. 
Throughout the code, character arrays (C-style strings) are used to represent
 and process user commands and file paths.

2. **Linked Lists:** A simple linked list data structure is used to manage the command history. 
The `CommandNode` structure is defined to store individual commands and create a linked list of
 command history entries.

3. **Arrays:** Arrays are used in the code for various purposes, 
including storing user input, representing command history entries, and handling command execution.

4. **Forked Processes (Windows API):** While the code does not use forked processes 
(as it's primarily designed for Windows), it does use the Windows API to create new processes. The `CreateProcess` function is used to execute external commands and programs.

These data structures are fundamental to the functionality of the terminal shell implemented in the code. They allow for the storage of commands, user input, and the execution of external processes, which are core components of a command-line shell.
