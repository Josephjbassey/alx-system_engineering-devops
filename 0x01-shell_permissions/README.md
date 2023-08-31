# Shell Permissions Project

This project covers various tasks related to shell permissions and aims to help you gain a deeper understanding of Linux file permissions and related commands.

## Learning Objectives

By the end of this project, you should be able to explain the following concepts:

- The purpose and usage of commands like `chmod`, `sudo`, `su`, `chown`, and `chgrp`.
- Linux file permissions and how to represent them using a single digit.
- How to change permissions, owner, and group of a file.
- The reasons why a normal user can't use `chown` on a file.
- How to execute commands with root privileges.
- Changing user ID and becoming a superuser.
- Creating users and groups, printing user and group information.

## Resources

To complete this project, refer to the following resources:

 - [Learning the shell - Permissions](http://linuxcommand.org/lc3_lts0090.php)
- Reading materials or videos related to permissions.
- Manual pages for commands like `chmod`, `sudo`, `su`, `chown`, `chgrp`, `id`, `groups`, `whoami`, `adduser`, `useradd`, and `addgroup`.

## General Requirements

- Editors allowed: vi, vim, emacs.
- All scripts will be tested on Ubuntu 20.04 LTS.
- All scripts should be exactly two lines long (`$ wc -l file` should print 2).
- All files should end with a new line.
- The first line of all files should be exactly `#!/bin/bash`.
- Create a `README.md` file in the project's root folder to describe each script's purpose.
- Do not use backticks, `&&`, `||`, or `;`.
- All files must be executable.

## Project Tasks

Here's a summary of the tasks you need to complete:

0. **My name is Betty**
   - Create a script to switch the current user to the user `betty`.

1. **Who am I**
   - Write a script to print the effective username of the current user.

2. **Groups**
   - Create a script to print all groups the current user is part of.

3. **New owner**
   - Write a script to change the owner of the file `hello` to the user `betty`.

4. **Empty!**
   - Write a script to create an empty file called `hello`.

5. **Execute**
   - Create a script to add execute permission to the owner of the file `hello`.

6. **Multiple permissions**
   - Write a script to add execute permission to the owner and group owner, and read permission to other users, to the file `hello`.

7. **Everybody!**
   - Create a script to add execution permission to the owner, group owner, and other users for the file `hello`.

8. **James Bond**
   - Write a script to set the permission of the file `hello` as specified.

9. **John Doe**
   - Create a script to set the mode of the file `hello` as specified.

10. **Look in the mirror**
    - Write a script to set the mode of the file `hello` the same as `olleh`'s mode.

11. **Directories**
    - Create a script to add execute permission to all subdirectories of the current directory for owner, group owner, and other users.

12. **More directories**
    - Write a script to create a directory called `my_dir` with specific permissions.

13. **Change group**
    - Create a script to change the group owner of the file `hello` to `school`.

14. **Owner and group**
    - Write a script to change the owner and group owner for all files and directories in the working directory.

15. **Symbolic links**
    - Create a script to change the owner and group owner of `_hello` to specific values.

16. **If only**
    - Write a script to change the owner of the file `hello` to `betty` only if it is owned by the user `guillaume`.

17. **Star Wars**
    - There's no specific task here, but you can explore playing Star Wars Episode IV in the terminal.

Remember to create separate script files for each task and include a description of each script in the `README.md` file.

## Authors

- [@josephjbassey](https://www.github.com/josephjbassey)


