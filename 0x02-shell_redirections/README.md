#!/bin/bash
echoHello, World : a script that prints output.

echo "\"(Ôo)'" : ignore " or special characters.
 
cat /etc/passwd : Display the content of the file.

cat two file : Display the content of thr two file.

tail -n 10 /etc/passwd : Display the last 10 line in the file.

head -n 10 /etc/passwd : Display the first 10 line in the file.

awk 'NR==3' iacta or cat iacta | head -n 3 | tail -n +3 : Display line 3 in the file.

\ : Display the special characters.

ls -al file : put the output of ls -al in the file.

find -name "*.js" -type f -delete: delete all file with .js in the current directory and all its subfolder.

find . -mindepth l -type d |wc -l: 
Write a script that counts the number of directories and sub-directories without the current and parent directories.

ls -t | head -n l0: display 10 newest file in the current directory.

sort | uniq -u : sort and display unique words.

grep 'root' /etc/passwd: Display lines containing the pattern “root” from the file /etc/passwd.

grep 'bin' /etc/passwd |wc -l: Display the number of lines that contain the pattern “bin” in the file /etc/passwd.

grep -A 3 'root' /etc/passwd: Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

cat /etc/passwd |grep -v 'bin': Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.





