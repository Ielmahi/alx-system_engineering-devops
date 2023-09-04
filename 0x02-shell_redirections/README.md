# 0x02. Shell, I/O Redirections and Filters
In this project, I've learned and practiced several key command-line tools, including "head", "tail", "find", "wc", "sort", "uniq", "grep", and "tr", for efficient text and file manipulation in the Shell. I've gained expertise in redirecting input and output, understanding special characters, and using these commands for data extraction and processing. These skills are essential for data analysis, system administration, and automation in Unix-like environments.

### Script Tasks: 
0. Hello World
* hello_world: Shell script that prints "Hello, World" followed by a new line to the standard output.
1. Confused smiley
* confused_smiley: Shell script that displays a confused smiley "(Ôo)'.
2. Let's display a file
* hellofile: Shell script that displays the content of the /etc/passwd file.
3. What about 2?
* twofiles: Shell script that displays the content of etc/passwd and /etc/hosts.
4. Last lines of a file
* lastlines: Shell script that displays the last 10 lines of /etc/passwd.
5. I'd prefer the first ones actually
* firstlines: Shell script that displays the first 10 lines of /etc/passwd.
6. Line #2
* third_line: Shell script that displays the third line of the file iacta.
7. It is a good file that cuts iron without making a noise
* shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
8. Save current state of directory
* script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
9. Duplicate last line
* Shell script that duplicates the last line of the file iacta.
10. No more javascript
* Shell script that deletes all the regular files (not directories) with a .js extension that are present in the current directory and all its subfolders.
11. Don't just count your directories, make your directories count.
* Shell script that counts the number of directories and sub-directories in the current directory, not including the current and parent directories but counting hidden ones.
12. What’s new
* Shell script that displays the 10 newest files in the current directory, one file per line, sorted from newest to oldest.
13. Being unique is better than being perfect
* Shell script that takes a list of words as input and only prints words that appear exactly once, one word per line, sorted.
14. It must be in that file
* Shell script that displays lines containing the pattern "root" from the file /etc/passwd.
15. Count that word
* Shell script that displays the number of lines containing the pattern "bin" in the file /etc/passwd.
16. What's next?
* Shell script that displays lines containing the pattern "root" and 3 lines after them in the file /etc/passwd.
17. I hate bins
* Shell script that displays all lines in the file /etc/passwd that do not contain the pattern "bin".
18. Letters only please
* Shell script that displays all lines of the file /etc/ssh/sshd_config starting with a letter, including capital letters.
19. A to Z
* Shell script that replaces all characters A and c from input to Z and e respectively.
20. Without C, you would live in hiago
* Shell script that removes all letters c and C from input.
21. esreveR
* Shell Bash script that reverses its input.
22. DJ Cut Killer
* Shell script that displays all users and their home directories, sorted by users, based on the /etc/passwd file.
23. Empty casks make the most noise
* Shell script that finds all empty files and directories in the current directory and all sub-directories as follows:
Only the names of the files and directories are displayed.
Hidden files included.
One file name per line.
24. A gif is worth ten thousand words
* Shell script that lists all the files with a .gif extension in the current directory and all its sub-directories as follows:
Hidden files included.
Only regular files (not directories) listed.
File names displayed without extensions.
Files sorted by byte values, but case insensitive.
One file name per line.
25. Acrostic
* Shell script that decodes acrostics that use the first letter of each line.
26. The biggest fan
* Shell script that parses web server logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests. Ordered by number of requests, with most active hosts or IP's at the top.
