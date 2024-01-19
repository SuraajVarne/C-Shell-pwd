## CSCE 3600 Shell Project

The CSCE 3600 Shell Project is a command-line interpreter developed as part of a Systems Programming class assignment. It provides a versatile and user-friendly environment for executing commands with features like interactive and batch modes, command history, custom aliases, and customizable prompts.

## Features
Interactive Mode: Execute commands interactively, accessing a rich set of features.
Batch Mode: Run commands from a batch file, with echoing for visibility.
Alias Support: Create and manage custom aliases for command shortcuts.
Command History: Track up to 20 commands, with options to print, clear, and retrieve from history.
Customizable Prompts: Tailor the shell prompt to your preferences.
Optional Functionality: Explore extra features like prompt customization and pipelining (for teams of 3 or 4).


## Getting Started


Compilation:

bash
Copy code
gcc shell.c myHistory.c alias.c -o shell
Run Interactive Mode:

bash
Copy code
./shell
Run Batch Mode:

bash
Copy code
./shell batch_test.txt
Optional Functionality
For teams completing all requirements, consider exploring optional functionalities such as prompt customization and pipelining.


## Notes


This project adheres to specified requirements while incorporating additional features for an enhanced user experience. Dive into the source code to explore the capabilities of this command-line interpreter.
