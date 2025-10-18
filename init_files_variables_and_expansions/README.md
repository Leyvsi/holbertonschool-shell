# IO Redirections and Filters

This repository contains shell scripts for learning about **input/output redirections** and **filters** in Linux. Each script demonstrates a specific task related to files, streams, and command manipulation.

## Scripts

| Script | Description |
|--------|-------------|
| 0-hello_world | Prints "Hello, World" to standard output. |
| 1-confused_smiley | Prints a confused smiley `(Ôo)'`. |
| 2-hellofile | Displays the content of `/etc/passwd`. |
| 3-twofiles | Displays the content of `/etc/passwd` and `/etc/hosts`. |
| 4-lastlines | Displays the last 10 lines of `/etc/passwd`. |
| 5-firstlines | Displays the first 10 lines of `/etc/passwd`. |
| 6-third_line | Displays the third line of the file `iacta`. |
| 7-file | Creates a file with a very specific name containing "Best School". |
| 8-ls_cwd_content | Saves the current directory listing to a file. |
| 9-duplicate_last_line | Duplicates the last line of the file `iacta`. |
| 10-no_more_js | Deletes all `.js` files in the current directory and subdirectories. |
| 11-directories_count | Counts the number of directories and subdirectories. |
| 12-newest_files | Displays the 10 newest files in the current directory. |
| 13-unique | Prints only words that appear exactly once from input. |
| 14-groups | Displays lines containing "root" in `/etc/passwd`. |
| 15-count_bin_lines | Counts lines containing "bin" in `/etc/passwd`. |
| 16-whats_next | Displays lines containing "root" and 3 lines after them. |
| 17-no_bin | Displays lines that do not contain "bin". |
| 18-letters_only | Displays lines starting with a letter in `/etc/ssh/sshd_config`. |
| 19-transformation | Replaces all `A` with `Z` and all `c` with `e`. |
| 20-no_C | Removes all letters `c` and `C` from input. |
| 21-reverse | Reverses the input. |
| 22-users_and_homes | Displays users and their home directories sorted by user. |
| 0-alias | Creates an alias `ls` that runs `rm -f *`. |

## Usage

Each script can be run as follows:

```bash
./script_name
