# Shell I/O Redirection

Project done during **Full Stack Software Engineering studies** at **ALX**. It aims to learn about __How to:__ 
* Rredirect standard output to a file.
* Get standard input from a file instead of the keyboard.
* Send the output from one program to the input of another program.
* Combine commands and filters with redirections.
* Use these commands (`head`, `tail`, `find`, `wc`, `sort`, `tr`, ... ).

## Files
All of the following files are scripts.

> * [0-hello_world](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/0-hello_world)
>> A script that prints `Hello, World`, followed by a new line to the standard output.
------------------
> * [1-confused_smiley](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/1-confused_smiley)
>> A script that displays a confused smiley `"(Ôo)'`.
------------------
> * [2-hellofile](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/2-hellofile)
>> A script that display the content of the `/etc/passwd` file.
------------------
> * [3-twofiles](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/3-twofiles)
>> A script that display the content of `/etc/passwd` and `/etc/hosts`.
------------------
> * [4-lastlines](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/4-lastlines)
>> A script that display the last 10 lines of `/etc/passwd`.
------------------
> * [5-firstlines](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/5-firstlines)
>> A script that display the first 10 lines of `/etc/passwd`.
------------------
> * [6-third_line](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/6-third_line)
>> A script that displays the third line of the file `iacta`.
------------------
> * [7-file](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/7-file)
>> A script that creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)`, containing the text `Best School` ending by a new line.
------------------
> * [8-cwd_state](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/8-cwd_state)
>> A script that writes into the file `ls_cwd_content` the result of the command `ls -la`. If the file `ls_cwd_content` already exists, it should be overwritten. If the file `ls_cwd_content` does not exist, create it.
------------------
> * [9-duplicate_last_line](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/9-duplicate_last_line)
>> A script that duplicates the last line of the file `iacta`.
------------------
> * [10-no_more_js](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/10-no_more_js)
>> A script that deletes all the regular files _(not the directories)_ with a `.js` extension that are present in the current directory and all its subfolders.
------------------
> * [11-directories](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/11-directories)
>> A script that counts the number of directories and sub-directories in the current directory.
------------------
> * [12-newest_files](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/12-newest_files)
>> A script that displays the 10 newest files in the current directory.
------------------
> * [13-unique](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/13-unique)
>> A script that takes a list of words as input and prints only words that appear exactly once.
------------------
> * [14-findthatword](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/14-findthatword)
>> A script that display lines containing the pattern `“root”` from the file `/etc/passwd`.
------------------
> * [15-countthatword](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/15-countthatword)
>> A script that display the number of lines that contain the pattern `“bin“` in the file `/etc/passwd`.
------------------
> * [16-whatsnext](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/16-whatsnext)
>> Display lines containing the pattern `“root”` and 3 lines after them in the file `/etc/passwd`.
------------------
> * [17-hidethisword](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/17-hidethisword)
>> A script that display all the lines in the file `/etc/passwd` that do not contain the pattern `“bin”`.
------------------
> * [18-letteronly](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/18-letteronly)
>> A script that display all lines of the file `/etc/ssh/sshd_config` starting with a letter.
>>> _including capital letters as well_
------------------
> * [19-AZ](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/19-AZ)
>> A script that replace all characters `A` and `c` from input to `Z` and `e` respectively.
------------------
> * [20-hiago](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/20-hiago)
>> A script that removes all letters `c` and `C` from input.
------------------
> * [21-reverse](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/21-reverse)
>> A script that reverse its input.
------------------
> * [22-users_and_homes](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/22-users_and_homes)
>> A script that displays all users and their home directories, sorted by users.
------------------
> * [100-empty_casks](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/100-empty_casks)
>> A script that finds all empty files and directories in the current directory and all sub-directories.
------------------
> * [101-gifs](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/101-gifs)
>> A script that lists all the files with a `.gif` extension in the current directory and all its sub-directories.
------------------
> * [102-acrostic](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/102-acrostic)
>> A script that decodes acrostics that use the first letter of each line.
>>> `An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval.`
------------------
> * [103-the_biggest_fan](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/103-the_biggest_fan)
>> A script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
>>> _Order by number of requests, most active host or IP at the top._
