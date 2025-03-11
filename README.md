# Ex-01-Linux-Commands

NAME : BHARATHI M K
REG NO : 212223040026

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
![image](https://github.com/user-attachments/assets/51e4cc94-2f80-4319-ad61-5c2bc9655d56)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![image](https://github.com/user-attachments/assets/d646479e-adf9-4800-908a-55582fcf9408)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![image](https://github.com/user-attachments/assets/ab415393-6150-46ef-a302-3e96ee322e37)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
![image](https://github.com/user-attachments/assets/e96ac152-c747-4d7f-843f-366d1558aa05)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![Screenshot 2025-03-11 131930](https://github.com/user-attachments/assets/13637293-c37f-4f41-90fe-e9762eb92881)

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
[Screenshot 2025-03-11 132234](https://github.com/user-attachments/assets/e7634e89-dbd9-4cbb-b741-279c35cdc8b0)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![Screenshot 2025-03-11 132309](https://github.com/user-attachments/assets/d68cfbff-3b7b-4587-9c37-83f46e80950e)

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![Screenshot 2025-03-11 132328](https://github.com/user-attachments/assets/c59af670-0b7b-4c9d-a6a5-e1ce252902a3)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
![Screenshot 2025-03-11 132347](https://github.com/user-attachments/assets/9e48faed-16a5-4a12-9f6e-17170625d04e)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
![Screenshot 2025-03-11 132406](https://github.com/user-attachments/assets/852ac176-3e61-460a-b02b-04955c52ee2d)
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
![Screenshot 2025-03-11 132718](https://github.com/user-attachments/assets/37ad2edc-5f2b-493c-9d0d-392bcd799c58)

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![Screenshot 2025-03-11 132735](https://github.com/user-attachments/assets/27c48a6c-f87b-4d0c-b095-196860d9e19f)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
![Screenshot 2025-03-11 132817](https://github.com/user-attachments/assets/f96d824c-82d6-4a7b-9959-87b2853a0aab)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
![Screenshot 2025-03-11 132838](https://github.com/user-attachments/assets/d0aeed95-f145-43d8-b9f1-6fbc284ca103)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
![Screenshot 2025-03-11 132854](https://github.com/user-attachments/assets/fa3be1f0-8784-4578-b5b5-62e9f1a4ba55)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr 
<'old'> <'new'>
![Screenshot 2025-03-11 133005](https://github.com/user-attachments/assets/986aa342-f488-4635-b2e6-3a5ae38441f4)

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
![Screenshot 2025-03-11 133533](https://github.com/user-attachments/assets/252b9245-522d-4359-9a2e-8a58d37d6dbb)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
![Screenshot 2025-03-11 133114](https://github.com/user-attachments/assets/89e84033-18cb-44ae-bcd6-abf455e8d02d)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
![Screenshot 2025-03-11 133600](https://github.com/user-attachments/assets/8ac5caec-84f7-45a9-ba13-68ed74ca94a7)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
![Screenshot 2025-03-11 133146](https://github.com/user-attachments/assets/996fbba4-bea3-42e8-83d2-652dd0157a5b)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
![Screenshot 2025-03-11 133204](https://github.com/user-attachments/assets/15b0d89e-6939-4301-82e1-9457f952702f)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
![Screenshot 2025-03-11 133231](https://github.com/user-attachments/assets/6d4bc0a7-9ab7-40a2-a432-6ffc0f72e634)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![Screenshot 2025-03-11 133249](https://github.com/user-attachments/assets/657584a4-ebbb-407d-a6e9-1bd261ff2ada)

### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
![Screenshot 2025-03-11 133308](https://github.com/user-attachments/assets/b99131a1-1ae7-4955-94bb-d638a5e8eeb1)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![Screenshot 2025-03-11 133323](https://github.com/user-attachments/assets/b7036427-7bfb-4bf8-ab9f-e4b9a42dced0)

### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
![Screenshot 2025-03-11 133404](https://github.com/user-attachments/assets/c962ff00-7c03-4baf-8ea2-bb2f932447f9)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

## Result:
Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.




















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
