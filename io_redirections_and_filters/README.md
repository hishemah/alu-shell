# Shell, I/O Redirections and filters

Two-line Bash scripts using redirections, pipes and filters (`cat`, `head`, `tail`, `grep`, `cut`, `tr`, `sort`, `uniq`, `find`, `rev`, `paste`).

| File | Description |
| ---- | ----------- |
| `0-hello_world` | Prints `Hello, World` followed by a new line |
| `1-confused_smiley` | Displays a confused smiley `"(Ôo)'` |
| `2-hellofile` | Displays the content of `/etc/passwd` |
| `3-twofiles` | Displays the content of `/etc/passwd` and `/etc/hosts` |
| `4-lastlines` | Displays the last 10 lines of `/etc/passwd` |
| `5-firstlines` | Displays the first 10 lines of `/etc/passwd` |
| `6-third_line` | Displays the third line of the file `iacta` |
| `7-file` | Creates a file with a name full of special characters containing `Best School` |
| `8-cwd_state` | Writes the result of `ls -la` into `ls_cwd_content` |
| `9-duplicate_last_line` | Duplicates the last line of the file `iacta` |
| `10-no_more_js` | Deletes all regular `.js` files in the current directory and subfolders |
| `11-directories` | Counts the directories and sub-directories in the current directory |
| `12-newest_files` | Displays the 10 newest files in the current directory |
| `13-unique` | Prints the words that appear exactly once in the input, sorted |
| `14-findthatword` | Displays the lines of `/etc/passwd` containing `root` |
| `15-countthatword` | Counts the lines of `/etc/passwd` containing `bin` |
| `16-whatsnext` | Displays lines containing `root` and the 3 lines after them |
| `17-hidethisword` | Displays the lines of `/etc/passwd` not containing `bin` |
| `18-letteronly` | Displays the lines of `/etc/ssh/sshd_config` starting with a letter |
| `19-AZ` | Replaces `A` with `Z` and `c` with `e` in the input |
| `20-hiago` | Removes all `c` and `C` letters from the input |
| `21-reverse` | Reverses its input |
| `22-users_and_homes` | Displays all users and their home directories, sorted by user |
| `23-empty_casks` | Lists the names of all empty files and directories, recursively |
| `24-gifs` | Lists `.gif` files recursively, without extension, sorted case-insensitively |
| `25-acrostic` | Decodes acrostics using the first letter of each line |
| `26-the_biggest_fan` | Displays the 11 hosts or IPs with the most requests from a TSV log |
