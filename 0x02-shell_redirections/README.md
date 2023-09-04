# Shell Scripting Tasks - DevOps Project

This repository contains my solutions to the Shell scripting tasks as part of the DevOps project. These tasks cover various aspects of shell scripting, including I/O redirection and filters.

## Table of Contents



1. [Task 0: Hello World](#task-0-hello-world)
2. [Task 1: Confused Smiley](#task-1-confused-smiley)
3. [Task 2: Let's Display a File](#task-2-lets-display-a-file)
4. [Task 3: What About 2?](#task-3-what-about-2)
5. [Task 4: Last Lines of a File](#task-4-last-lines-of-a-file)
6. [Task 5: I'd Prefer the First Ones Actually](#task-5-id-prefer-the-first-ones-actually)
7. [Task 6: Line #2](#task-6-line-2)
8. [Task 7: It is a Good File That Cuts Iron Without Making a Noise](#task-7-it-is-a-good-file-that-cuts-iron-without-making-a-noise)
9. [Task 8: Save Current State of Directory](#task-8-save-current-state-of-directory)
10. [Task 9: Duplicate Last Line](#task-9-duplicate-last-line)
11. [Task 10: No More JavaScript](#task-10-no-more-javascript)
12. [Task 11: Don't Just Count Your Directories, Make Your Directories Count](#task-11-dont-just-count-your-directories-make-your-directories-count)
13. [Task 12: What’s New](#task-12-whats-new)
14. [Task 13: Being Unique is Better Than Being Perfect](#task-13-being-unique-is-better-than-being-perfect)
15. [Task 14: It Must Be in That File](#task-14-it-must-be-in-that-file)
16. [Task 15: Count That Word](#task-15-count-that-word)
17. [Task 16: What's Next?](#task-16-whats-next)
18. [Task 17: I Hate Bins](#task-17-i-hate-bins)
19. [Task 18: Letters only please](#task-18-letters-only-please)
20. [Task 19: A to Z](#task-19-a-to-z)
21. [Task 20: Without C, you would live in hiago](#task-20-without-c-you-would-live-in-hiago)
22. [Task 21: esreveR](#task-21-esrever)
23. [Task 22: DJ Cut Killer](#task-22-dj-cut-killer)
24. [Task 23: Empty casks make the most noise](#task-23-empty-casks-make-the-most-noise)
25. [Task 24: A gif is worth ten thousand words](#task-24-a-gif-is-worth-ten-thousand-words)
26. [Task 25: Acrostic](#task-25-acrostic)
27. [Task 26: The biggest fan](#task-26-the-biggest-fan)

## Task Descriptions

### Task 0: Hello World (mandatory)
This is a simple "Hello, World!" script.

Usage:
```bash
./0-hello_world
```

### Task 1: Confused Smiley (mandatory)
This script displays a confused smiley: `"(Ôo)'`.

Usage:
```bash
./1-confused_smiley
```

### Task 2: Let's Display a File (mandatory)
This script displays the content of a file named `/etc/passwd`.

Usage:
```bash
./2-hellofile
```

### Task 3: What About 2? (mandatory)
This script displays the content of a file named `/etc/passwd` and `/etc/hosts`.

Usage:
```bash
./3-let_me_in
```

### Task 4: Last Lines of a File (mandatory)
This script displays the last 10 lines of a file named `/etc/passwd`.

Usage:
```bash
./4-lastlines
```

### Task 5: I'd Prefer the First Ones Actually (mandatory)
This script displays the first 10 lines of a file named `/etc/passwd`.

Usage:
```bash
./5-firstlines
```

### Task 6: Line #2 (mandatory)
This script displays the third line of a file named `/etc/passwd`.

Usage:
```bash
./6-third_line
```

### Task 7: It is a Good File That Cuts Iron Without Making a Noise (mandatory)
This script creates a file named `/tmp/for_the_record` with specific content.

Usage:
```bash
./7-file
```

### Task 8: Save Current State of Directory (mandatory)
This script saves the current directory path to a file named `/tmp/current_directory`.

Usage:
```bash
./8-cwd_state
```

### Task 9: Duplicate Last Line (mandatory)
This script duplicates the last line of a file named `/etc/passwd` and saves it to `/tmp/duplicated_line`.

Usage:
```bash
./9-duplicate_last_line
```

### Task 10: No More JavaScript (mandatory)
This script replaces all occurrences of "javascript" with "JAVASCRIPT" in the input text.

Usage:
```bash
echo 'This is a javascript example.' | ./10-no_more_js
```

### Task 11: Don't Just Count Your Directories, Make Your Directories Count (mandatory)
This script counts the number of directories in the current directory and its subdirectories.

Usage:
```bash
./11-directories_count
```

### Task 12: What’s New (mandatory)
This script displays the 11 most recently modified files in the current directory and its subdirectories.

Usage:
```bash
./12-newest_files
```

### Task 13: Being Unique is Better Than Being Perfect (mandatory)
This script takes a list of words as input and displays only the words that appear once.

Usage:
```bash
./13-unique
```

### Task 14: It Must Be in That File (mandatory)
This script searches for a specific string in a file named `/etc/passwd` and displays the line containing that string.

Usage:
```bash
./14-find_that_string
```

### Task 15: Count That Word (mandatory)
This script counts the occurrences of a specific word in a file named `/etc/passwd`.

Usage:
```bash
./15-count_that_word
```

### Task 16: What's Next? (mandatory)
This script displays the lines in a file named `/etc/passwd` that match a specific pattern.

Usage:
```bash
./16-grep_that_pattern
```

### Task 17: I Hate Bins (mandatory)
This script lists all files in the current directory and its subdirectories, sorted by byte values.

Usage:
```bash
./17-hidethosebins
```

### Task 18: Letters only please (mandatory)
This script filters and displays all lines of the file `/etc/ssh/sshd_config` that start with a letter, including capital letters.

Usage:
```bash
./18-letteronly
```

### Task 19: A to Z (mandatory)
Replace all occurrences of characters 'A' with 'Z' and 'c' with 'e' in the input text.

Usage:
```bash
echo 'Replace all characters "A" and "c" from input to "Z" and "e".' | ./19-AZ
```

### Task 20: Without C, you would live in hiago (mandatory)
Create a script that removes all instances of the letter 'c' (both uppercase and lowercase) from the input text.

Usage:
```bash
echo 'Chicago' | ./20-hiago
```

### Task 21: esreveR (mandatory)
Write a script that reverses its input text.

Usage:
```bash
echo "Reverse" | ./21-reverse
```

### Task 22: DJ Cut Killer (mandatory)
This script displays all users and their home directories, sorted by users, based on the `/etc/passwd` file.

Usage:
```bash
./22-users_and_homes
```

### Task 23: Empty casks make the most noise (advanced)
Find and display all empty files and directories in the current directory and its subdirectories. Only the names of the files and directories are displayed, and hidden files are listed.

Usage:
```bash
./100-empty_casks
```

### Task 24: A gif is worth ten thousand words (advanced)
List all files with a .gif extension in the current directory and its subdirectories. Only regular files (not directories) are listed, and the names are displayed without their extensions. The files are sorted by byte values in a case-insensitive manner.

Usage:
```bash
./101-gifs
```

### Task 25: Acrostic (advanced)
This script decodes acrostics that use the first letter of each line.

Usage:
```bash
./102-acrostic < input_file
```

### Task 26: The biggest fan (advanced)
Parse web server logs in TSV format and display the top 11 hosts or IP addresses that made the most requests, ordered by the number of requests.

Usage:
```bash
./103-the_biggest_fan < logs_file.tsv
```
