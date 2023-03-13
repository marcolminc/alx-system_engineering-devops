# 0x02-Shell Redirections

each script is described how it works/ what it produces

## Table of Contents

- [0.](#0-hello_world)
- [1.] (#1-confused_smiley)
- [2.] (#2-hellofile)
- [3.] (#3-twofiles)
- [4.] (#4-lastlines)
- [5.] (#5-firstlines)
- [6.] (#6-third_line)

## 0-hello world

prints "Hello, World", followed by a new line to the stdout. using echo.

## 1-confused_smiley

displays a confused smiley "(Ôo)'. Using \" to escape the apostrophe.

## 2-hellofile

Display the content of the /etc/passwd file. Using less.

## 3-twofiles

Display the content of /etc/passwd and /etc/hosts. Using cat file1 file2.

## 4-lastlines

Display the last 10 lines of /etc/passwd. Using tail.

## 5-firstlines

Displays the first 10 lines. Using head.

## 6-third_line

This command uses head to display the first three lines of "filename.txt", and then pipes the output to tail with the -n 1 option, which displays only the last line of the output. Since the output of head is the first three lines of the file, the third line will be the last line of the output, and tail will display it.
head -n 3 iacta | tai -n 1

