# Unix-like Shell in C

## Overview

Welcome to the Unix-like Shell project, a command-line interface developed in C that emulates the functionality of a Unix shell. This shell allows users to interact with their system, execute commands, and automate tasks with ease. Whether you're a developer, system administrator, or just curious about how shells work, this project provides an educational and functional tool for your needs.

## Features

- **Interactive and Batch Modes:** The Unix-like shell offers both interactive mode, where you can enter commands in real-time, and batch mode, where you can execute a list of commands from a file, making it versatile for different scenarios.

- **Command History:** Never lose track of your commands. The shell maintains a command history, allowing you to navigate and rerun previous commands with ease.

- **Alias Support:** Simplify command execution with custom aliases. You can create, manage, and use aliases for frequently used commands.

- **Pipelining:** Harness the power of pipelining by chaining multiple commands together. Redirect input and output streams to create intricate command sequences.

- **System Calls Optimization:** This shell is optimized for performance. Key system calls like `fork()`, `exec()`, and `pipe()` have been fine-tuned to reduce command execution time, improving overall system responsiveness.

## Getting Started

### Prerequisites

Before you can start using the Unix-like shell, ensure you have the following prerequisites installed:

- **C Compiler:** You'll need a C compiler such as GCC to compile the source code.
- **Linux or Unix-like OS:** The shell is designed to work on Linux-based systems.

### Compilation

To compile the Unix-like shell, use the provided Makefile:

```shell
make
