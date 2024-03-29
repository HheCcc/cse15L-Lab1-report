# Lab1 Report


## For the command `cd`
1. An example of using the command with no arguments.
```
[user@sahara ~]$ cd
[user@sahara ~]$
```
* The working directory is `/home`
* `cd` is used to change the currentr diretory to others. Since there is no directory after the commond `cd`.
* The output is not an error
2. An example of using the command with a path to a directory as an argument.
```
[user@sahara ~]$ cd lecture1
[user@sahara ~/lecture1]$
```
* The working directory is `/lecture1`
* I use `cd` to change the directory from `/home` to `/lecture1`
* The output is not an error
3. An example of using the command with a path to a file as an argument.
```
[user@sahara ~]$ cd lecture1/Hello.java
bash: cd: lecture1/Hello.java: Not a directory
[user@sahara ~]$
```
* The working directory is `/home`
* We only use `cd`to change the directory
* The output is an error, cuz we can't use `cd` to a file, Hello.java is a file not a directory

## For the command `ls`
1. An example of using the command with no arguments.
```
[user@sahara ~]$ ls
lecture1
[user@sahara ~]$
```
* The working directory is `/home`
* `ls` lists the folder in `/home`
* It's not an error
2. An example of using the command with a path to a directory as an argument.
```
[user@sahara ~]$ ls lecture1
Hello.class  Hello.java  messages  README
[user@sahara ~]$
```
* The working directory is `/home`
* `ls` lists the folders and files in `/picture1`
* It's not an error
3. An example of using the command with a path to a file as an argument.
```
[user@sahara ~]$ ls lecture1/Hello.java
lecture1/Hello.java
[user@sahara ~]$
```
* The working directory is `/home`
* `ls` lists the folders and files in the path
* It's not an error

## For the command `cat`
1. An example of using the command with no arguments.
```
[user@sahara ~]$ cat
```
* The working directory is `/home`
* `cat` used to print the contents of files given by the paths
* It's not an error

2. An example of using the command with a path to a directory as an argument.
```
[user@sahara ~]$ cat lecture1
cat: lecture1: Is a directory
[user@sahara ~]$
```
* The working directory is `/home`
* `cat` used to print the contents of files given by the paths
* It's an error, lecture1 is a direcotry, can't be printed.

3. An example of using the command with a path to a file as an argument.
![Images](Pics.png)
* The working directory is `/home`
* `cat` used to print the contents of files given by the paths
* It's not an error

