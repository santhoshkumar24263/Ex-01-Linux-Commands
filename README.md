# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls
![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/5a548882-ca44-47da-a515-b114835cec33)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/e0e389df-9662-4bc1-8d2c-210f05a23d21)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/eca6d56e-7be2-47b6-b57f-370b6f7fbbbc)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/b1a05bee-9b2e-42f6-a7f8-719094bdae62)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/29a3bb96-be70-4e0b-9eb4-01f008814584)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/83fc5030-5baf-4de6-b542-ba141facce74)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/a19ab138-c1ea-419d-b913-ba57ee90c857)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/1adf338b-70ce-402a-98cb-44c6ca3a0b00)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/78f71e97-f470-4408-af16-3c3edd5b7b38)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/c1331474-37fc-49d5-8e3f-7f5b4fa2279e)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/bbacdacf-00da-42ee-a029-98d19a62b33e)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/16d6f00a-c4de-4f58-bdce-9db0b9a6deca)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/de15e0f1-c109-4656-9dbf-4b1c7b11e4ad)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/a11f0ca3-1b92-4bf1-a4bd-507faf12ab1f)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/8787e9d9-e086-4a7d-a1e1-f2f7f3e9d65e)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/0b5160ac-0468-4b3f-b860-bde8cdcbce54)

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/e7c23b38-0b2b-41d5-96e6-e0aa02f37b3a)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/e45a6b12-c85b-4fcb-aa3c-e1683e312b8e)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/22bde913-a06d-4c27-9d77-c3f4701127f1)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

 ![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/e9fc033d-62f2-4982-ba87-28b6c85c04ac)

### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/d2ac568b-eb29-402c-9c60-3f15d94fb3b4)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/3f8c1ca4-3c15-4b28-ab3e-ca5e5d3f61f5)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/bfb9cb67-c642-4b15-ad0d-4e9ffd835c76)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/46935395-d739-4902-afd6-f36d11045a51)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/a7a5f759-c2a0-40a8-baa7-b9da32c1f802)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/58f11506-ac4e-4aab-b74c-a11d170b39e5)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![image](https://github.com/knight7080/Ex-01-Linux-Commands/assets/88542035/7800efb2-209d-42ff-9940-a2d3a6716a5f)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
