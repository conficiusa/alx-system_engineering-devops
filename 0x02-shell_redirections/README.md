echo "Hello, World"
 prints “Hello, World”, followed by a new line to the standard output.

echo "\"(Ôo)'"
 displays a confused smiley "(Ôo)'.

cat /etc/passwd
Display the content of the /etc/passwd file.

{ cat /etc/passwd && echo "" && cat /etc/hosts; }
Display the content of /etc/passwd and /etc/hosts

tail /etc/passwd
display the last 10 lines of /etc/passwd

head -n 10 /etc/passwd
 first 10 lines of a file in Unix/Linux

ad -n 3 iacta | tail -n 1
displays the third line of the file iacta

echo "Best School" > '*\x5C\x2A\x5C\x5C\x27\x5C\x22Best School\x5C\x27\x5C\x5C\x2A\x24\x3F\x2A\x2A\x2A\x2A\x2A\x2A\x2A\x3A)' 
creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

ls -la > ls_cwd_content
t writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

tail -n 1 iacta >> iacta
script that duplicates the last line of the file iacta


find . -type f -name "*.js" -delete
script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
