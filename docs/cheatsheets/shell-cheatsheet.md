---
title: Shell Cheat Sheet
sidebar_position: 4
---

**Basics:**

- `ls`: List files and directories.
- `cd <directory>`: Change directory.
- `pwd`: Print Working Directory (shows your current location).
- `mkdir <directory>`: Create a new directory.
- `rm <file>` (use with caution!): Remove a file.
- `cp <source> <destination>`: Copy a file.
- `mv <source> <destination>`: Move or rename a file.

**Permissions:**

- `chmod <permissions> <file>` (use with caution!): Change file permissions.

**Navigation:**

- `..`: Move up one directory level.
- `~`: Go to your home directory.

**File Manipulation:**

- `cat <file>`: Display the contents of a file.
- `head <file>`: Show the first few lines of a file.
- `tail <file>`: Show the last few lines of a file.
- `more <file>`: View a file page by page.

**Searching:**

- `grep <pattern> <file>`: Search for a pattern in a file. (e.g., `grep error system.log` shows lines with "error" in system.log)

**Text Processing:**

- `awk '{print $1}' <file>`: Print the first column of a file using awk (field separator is space by default).

**Advanced:**

- `man <command>`: Get help documentation for a command.
- `history`: Show command history.
- `!number`: Run the command with the specified number from history.
- `*`: Wildcard for matching multiple characters in filenames.
- `(pipe) |`: Send the output of one command as input to another. (e.g., `ls | grep txt` shows only files with ".txt" extension)
- `>`, `>>`: Redirect output. (e.g., `ls > output.txt` saves the directory listing to output.txt, `ls >> output.txt` appends the listing)

**Remember:** Replace `<directory>`, `<file>`, `<permissions>`, and `<pattern>` with your specific details. Be cautious with file manipulation commands.
