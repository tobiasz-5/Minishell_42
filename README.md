Minishell:
a custom shell written in C, inspired by Bash. The project focuses on replicating essential shell functionalities while learning about system programming and process management.

Features:
Command execution: Supports basic commands, pipelines (|), and redirections (<, >, <<, >>).
Environment variables: Handles variable expansion ($ and $?, including proper behavior for heredoc expansion.
Process and signal management: Implements process creation, piping, and proper handling of signals like Ctrl+C, Ctrl+D and Ctrl+\.
Built-in commands: Includes echo, cd, pwd, export, unset, env, and exit.

Project Complexity:
Multiple process handling: Advanced use of system calls like fork, execve, and pipes to replicate real shell behavior.
Structured parsing: Lexical and syntactical analysis with support for cases like quote handling (" and ') and variable expansion.
Operating system interaction: Direct manipulation of environment variables and file descriptors.
Bash compliance: Mimics Bash behavior in complex scenarios, including signals, redirections, pipelines, and their combinations.

This project is a simplified implementation of a shell, focusing on functionality and a deeper understanding of how shells work.
