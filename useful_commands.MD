# Bash Command Cheat Sheet

A quick reference for common shell commands.

## Navigation

| Command | Description |
|---|---|
| `cd` | Change directory |
| `pwd` | Print working directory |
| `ls` | List contents |
| `ls -a` | List contents, including hidden files |
| `~` | Alias for home directory |

## Files & Directories

| Command | Description |
|---|---|
| `mkdir` | Make a new directory |
| `cp` | Copy a file or directory |
| `mv` | Move (or rename) a file or directory |
| `rm` | Remove a file or directory |
| `rm -r` | Remove recursively (for directories and their contents) |

> **Heads up:** `rm` is permanent — there's no trash bin to recover from. Double-check paths before running it, especially with `-r`.

## Viewing Files

| Command | Description |
|---|---|
| `cat` | View a file's contents all at once |
| `less` | View a file interactively (scrollable) |
| `nano` | Open a file in a simple text editor |

**`nano` shortcuts:**

- `Ctrl + O` — Save file
- `Ctrl + X` — Exit

## Network

| Command | Description |
|---|---|
| `curl` | Make web requests from the command line |

## Flags

| Flag | Meaning |
|---|---|
| `-r` | Recursive (apply to directories and their contents) |
| `-a` | All (include hidden files, e.g. with `ls`) |