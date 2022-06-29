# Shell: I/O Redirections & Filters

## Table of Content: 
<br />

| File | Script Description | 
--- | ---
<br/><span style="font-size: 1.7rem">**Mandatory**</span>
[0-hello_world](./0-hello_world) | Prints `“Hello, World”`, followed by a new line to the standard output
[1-confused_smiley](./1-confused_smiley) | Displays a confused smiley `"(Ôo)'`
[2-hellofile](./2-hellofile) | Displays the content of the `/etc/passwd` file
[3-twofiles](./3-twofiles) | Displays the content of `/etc/passwd` and `/etc/hosts`
[4-lastlines](./4-lastlines) | Displays the last 10 lines of `/etc/passwd`
[5-firstlines](./5-firstlines) | Displays the first 10 lines of `/etc/passwd`
[6-third_line](./6-third_line) | Write a script that displays the third line of the file iacta <br />The file iacta will be in the working directory <ul><li>You’re not allowed to use sed</li></ul>
[7-file](./7-file) | Creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School` ending by a new line
[8-cwd_state](./8-cwd_state) | Writes into the file `ls_cwd_content` the result of the command `ls -la` <br /> If the file `ls_cwd_content` already exists, it should be overwritten<br /> If the file `ls_cwd_content` does not exist, create it
[9-duplicate_last_line](./9-duplicate_last_line) | Duplicates the last line of the file `iacta` <ul><li>The file `iacta` will be in the working directory</li></ul>
[10-no_more_js](./10-no_more_js) | Deletes all the regular files (not the directories) with a `.js` extension that are present in the current directory and all its subfolders
[11-directories](./11-directories) | Counts the number of directories and sub-directories in the current directory. <ul><li>The current and parent directories should not be taken into account</li><li>Hidden directories should be counted</li></ul>
[12-newest_files](./12-newest_files) | Displays the 10 newest files in the current directory<br /> Requirements: <ul><li>One file per line</li><li>Sorted from the newest to the oldest</li></ul>
[13-unique](./13-unique) | Takes a list of words as input and prints only words that appear exactly once. <ul><li>Input format: One line, one word</li><li>Output format: One line, one word</li><li>Words should be sorted</li></ul>
[14-findthatword](./14-findthatword) | Displays lines containing the pattern `“root”` from the file `/etc/passwd`
[15-countthatword](./15-countthatword) | Displays the number of lines that contain the pattern `“bin”` in the file `/etc/passwd`
[16-whatsnext](./16-whatsnext) | Displays lines containing the pattern `“root”` and 3 lines after them in the file `/etc/passwd`
[17-hidethisword](./17-hidethisword) | Displays all the lines in the file `/etc/passwd` that do not contain the pattern `“bin”`
[18-letteronly](./18-letteronly) | Displays all lines of the file `/etc/ssh/sshd_config` starting with a letter
[19-AZ](./19-AZ) | Replaces all characters `A` and `c` from input to `Z` and `e` respectively
[20-hiago](./20-hiago) | Removes all letters `c` and `C` from input
[21-reverse](./21-reverse) | Reverses its input
[22-users_and_homes](./22-users_and_homes) | Displays all users and their home directories, sorted by users <ul><li>Based on the the /etc/passwd file</li></ul>
<br/><span style="font-size: 1.7rem">**Advanced** </span>
[100-empty_casks](./100-empty_casks) | Finds all empty files and directories in the current directory and all sub-directories <ul><li>Only the names of the files and directories should be displayed (not the entire path)</li><li>Hidden files should be listed</li><li>One file name per line</li><li>The listing should end with a new line</li><li>You are not allowed to use `basename`, `grep`, `egrep`, `fgrep` or `rgrep`</li></ul>
[101-gifs](./101-gifs) | Lists all the files with a .gif extension in the current directory and all its sub-directories.<ul><li>Hidden files should be listed</li><li>Only regular files (not directories) should be listed</li><li>The names of the files should be displayed without their extensions</li><li>The files should be sorted by byte values, but case-insensitive (file `aaa` should be listed before file `bbb`, file `.b` should be listed before file `a`, and file `Rona` should be listed after file `jay`)</li><li>One file name per line</li><li>The listing should end with a new line</li><li>You are not allowed to use `basename`, `grep`, `egrep`, `fgrep` or `rgrep`</li></ul>
[102-acrostic](./102-acrostic) | Decodes [Acrostics](https://en.wikipedia.org/wiki/Acrostic) that use the first letter of each line <ul><li>The ‘decoded’ message has to end with a new line</li><li>You are not allowed to use `grep`, `egrep`, `fgrep` or `rgrep`</li></ul>
[103-the_biggest_fan](./103-the_biggest_fan) | Parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests <ul><li>Order by number of requests, most active host or IP at the top</li><li>You are not allowed to use `grep`, `egrep`, `fgrep` or `rgrep`</li></ul>

# 
<br>

## **Author:** [Seun Ajayi](https://github.com/Seun-A)