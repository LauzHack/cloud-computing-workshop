# LauzHack Cloud Computing Workshop

This is the repository for the LauzHack Cloud Computing Workshop on 2024-11-21.

- [Slides](slides.pdf)
- [main.ipynb](main.ipynb)


# Terminal Basics 

Welcome to the **Terminal Basics**! This guide will help you navigate, manage files, and use essential commands in the terminal.

---

## Table of Contents
1. [Navigation Commands](#navigation-commands)
2. [File and Directory Management](#file-and-directory-management)
3. [Viewing and Editing Files](#viewing-and-editing-files)
4. [Searching Files](#searching-files)
5. [System and Process Information](#system-and-process-information)
6. [Permissions Management](#permissions-management)
7. [Useful Tips](#useful-tips)




---


## Navigation Commands


- **`pwd`**: Print the current directory.
  ```bash
  $ pwd
  ```
- **`ls`**: List files and directories.
  ```bash
  $ ls          # Basic list
  $ ls -a       # Include hidden files
  $ ls -l       # Detailed listing
  ```
- **`cd`**: Change directory.
  ```bash
  $ cd foldername       # Navigate to a folder
  $ cd ..               # Go up one directory
  $ cd /path/to/folder  # Move to a specific folder
  ```

---

## File and Directory Management

- **`touch`**: Create an empty file.
  ```bash
  $ touch filename.txt
  ```
- **`mkdir`**: Create a new directory.
  ```bash
  $ mkdir foldername
  ```
- **`rm`**: Remove files or directories.
  ```bash
  $ rm filename          # Delete a file
  $ rm -r foldername     # Delete a directory
  ```
- **`cp`**: Copy files or directories.
  ```bash
  $ cp source.txt destination.txt  # Copy a file
  $ cp -r folder1 folder2          # Copy a directory
  ```
- **`mv`**: Move or rename files.
  ```bash
  $ mv oldname.txt newname.txt     # Rename a file
  $ mv file.txt /path/to/folder    # Move a file
  ```

---

## Viewing and Editing Files

- **`cat`**: Display file contents.
  ```bash
  $ cat filename.txt
  ```
- **`nano`**: Edit files using Nano editor.
  ```bash
  $ nano filename.txt
  ```
- **`less`**: View large files one page at a time.
  ```bash
  $ less filename.txt
  ```

---

## Searching Files

- **`grep`**: Search for specific text in files.
  ```bash
  $ grep "keyword" filename.txt        # Search within a file
  $ grep -r "keyword" .                # Recursive search
  ```

---

## System and Process Information

- **`whoami`**: Display the current user.
  ```bash
  $ whoami
  ```
- **`top`**: View running processes in real-time.
  ```bash
  $ top
  ```
- **`df -h`**: Check disk space usage.
  ```bash
  $ df -h
  ```
- **`free -h`**: Display memory usage.
  ```bash
  $ free -h
  ```

---

## Permissions Management

- **`chmod`**: Change file permissions.
  ```bash
  $ chmod 755 filename
  ```
- **`chown`**: Change file ownership.
  ```bash
  $ chown user:group filename
  ```

---

## Useful Tips

- **Auto-complete with Tab**:
  Press `Tab` while typing a command or file name to auto-complete.

- **Command History**:
  Use `Up` and `Down` arrow keys to access previous commands.

- **Clear Terminal**:
  ```bash
  $ clear
  ```
  Or press `Ctrl + L`.

- **Interrupt Commands**:
  Press `Ctrl + C` to stop a running command.

- **Search Command History**:
  Use `Ctrl + R` to search through previous commands.
