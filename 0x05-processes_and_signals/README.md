# 0x05. Processes and Signals

This repository contains the source code and documentation for the "Processes and Signals" project, which is part of the Holberton School curriculum. The project focuses on understanding and working with processes and signals in the Linux environment.

## Project Overview

The "Processes and Signals" project aims to develop a deep understanding of processes and signals and their usage in the Linux operating system. Processes are instances of executing programs, while signals are software interrupts used to communicate between processes or within a single process. This project involves implementing various programs that showcase the usage of processes and signals.

## Project Structure

The project is structured as follows:

- **0-what-is-my-pid**: This script displays the process ID of the current running script.
- **1-list_your_processes**: This script lists all running processes on the system.
- **2-show_your_bash_pid**: This script displays the process ID of the current Bash session.
- **3-show_your_bash_pid_made_easy**: This script displays the process ID of the current Bash session using shorter syntax.
- **4-to_infinity_and_beyond**: This script runs an infinite loop using a `while` loop.
- **5-kill_me_now**: This script kills the process with a specified process ID.
- **6-kill_me_now_made_easy**: This script kills the process with a specified process ID using shorter syntax.
- **7-highlander**: This script displays and handles signals using the `trap` command.
- **8-beheaded_process**: This script kills the process with a specified process ID and prints a specific output.
- **9-process_and_pid_file**: This script starts and stops a process based on the contents of a PID file.
- **10-manage_my_process**: This script manages the lifetime of a process using signals.

## Usage

To use the scripts provided in this project, follow these steps:

1. Clone the repository: `git clone https://github.com/your_username/processes-signals.git`
2. Navigate to the project directory: `cd processes-signals`
3. Execute the desired script using the Bash interpreter. For example: `bash 0-what-is-my-pid`

Read the script comments and output to understand their functionality.

## Testing

Some of the scripts in this project have test cases to verify their functionality. Run the test cases using the following command:

```bash
bash tests/test_script.sh
```

Ensure you are in the project's root directory when executing the command.

## Contributing

Contributions to the project are welcome! If you find any issues or have suggestions for improvements, please create a pull request or submit an issue on the GitHub repository.
