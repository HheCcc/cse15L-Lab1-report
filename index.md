# Lab1 Report


## For the command 'cd'
1. An example of using the command with no arguments.
```
[user@sahara ~]$ cd
```
* The working directory is home
* cd is used to change the currentr diretory to others. Since there is no directory after the commond cd
* the output is an error, we should add diretory after cd.
2. An example of using the command with a path to a directory as an argument.
```
[user@sahara ~]$ cd lecture1
[user@sahara ~/lecture1]$
```
* The working directory is lecture1
* I use cd to change the directory from home to lecture1
* The output is not an error
3. An example of using the command with a path to a file as an argument.
```
[user@sahara ~]$ cd README
bash: cd: README: No such file or directory
[user@sahara ~]$
```
* The working directory is home
* We only use cd to change the directory
* The output is an error, cuz we can't use cd to a file

## For the command 'ls'
1. An example of using the command with no arguments.
```
[user@sahara ~]$ ls
lecture1
```
*
*
*
2. An example of using the command with a path to a directory as an argument.
```
[user@sahara ~]$ ls lecture1
Hello.class  Hello.java  messages  README
```
*
*
*
3. An example of using the command with a path to a file as an argument.
```
[user@sahara ~]$ ls README
ls: cannot access 'README': No such file or directory
```
*
*
*

## For the command 'cat'
1. An example of using the command with no arguments.
```
[user@sahara ~]$ cat
```
*
*
*
2. An example of using the command with a path to a directory as an argument.
```
[user@sahara ~]$ cat lecture1
cat: lecture1: Is a directory
```
*
*
*
3. An example of using the command with a path to a file as an argument.
```
[user@sahara ~]$ cat README
cat: README: No such file or directory
```
*
*
*

