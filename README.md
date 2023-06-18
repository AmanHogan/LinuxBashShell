# Aman Hogan-Bailey Command Line Shell

This repository contains a C program that implements a simple command line shell. It allows users to enter commands, execute them, and provides additional features such as command history and process tracking.

## Prerequisites

Before running the program, ensure that you have the following prerequisites:

- C compiler (e.g., GCC)

## How to Run

To run the command line shell program, follow these steps:

1. Clone the repository to your local machine.
2. Open a terminal or command prompt.
3. Navigate to the cloned repository directory.
4. Compile the program using the following command:

   ```bash
   gcc -o shell main.c
   ```

5. Run the program with the following command:

   ```bash
   ./shell
   ```

6. The program will start, displaying the shell prompt "msh>". You can now enter commands and execute them.

## Usage

The command line shell supports the following features:

- Entering commands: Simply type a command and press Enter to execute it.
- Command history: Use the "history" command to view the history of commands entered so far.
- Process tracking: The program keeps track of the processes executed. Use the "pidhistory" command to view the list of process IDs.
- Changing directories: Use the "cd" command followed by a directory path to change the current directory.
- Re-running commands from history: Enter "!n" (where n is the index of a command in history) to re-run a specific command from history.

## Examples

Here are a few examples of using the command line shell:

- Running a command:

  ```bash
  msh> ls
  ```

- Viewing command history:

  ```bash
  msh> history
  ```

- Re-running a command from history:

  ```bash
  msh> !2
  ```

- Changing directories:

  ```bash
  msh> cd /path/to/directory
  ```

## Exiting the Shell

To exit the shell, you can use either the "quit" or "exit" command. This will terminate the program and return you to the regular command prompt.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and use it according to your needs.

## Acknowledgments

This command line shell program was created as an assignment by Aman Hogan-Bailey.
