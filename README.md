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

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.
Syntax: pwd

### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.
Syntax: mkdir <directory name>

### 4)	rmdir Command

The rmdir command is used to delete a directory.
Syntax: rmdir <directory name>

<img width="432" height="326" alt="Screenshot_2025-08-29_09-36-33" src="https://github.com/user-attachments/assets/4e505649-f4a3-41ac-a758-b324ea4a7f78" />



### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="231" height="89" alt="image" src="https://github.com/user-attachments/assets/0efbd4f0-03b9-4bee-b392-1945d7105b63" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="343" height="139" alt="image" src="https://github.com/user-attachments/assets/a611967f-a6c9-4b11-a6b5-2b78561fa38a" />


 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="274" height="47" alt="image" src="https://github.com/user-attachments/assets/f6edce35-80fd-4e49-898c-6babfa141cd6" />


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="284" height="50" alt="image" src="https://github.com/user-attachments/assets/888e2f62-d09e-4477-832d-68e299aa6a6d" />


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="193" height="91" alt="image" src="https://github.com/user-attachments/assets/e053b40b-1df8-4f09-8048-595ebb797279" />



### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

<img width="210" height="92" alt="image" src="https://github.com/user-attachments/assets/9b41b684-6345-4919-b36a-49bce58d0f8c" />

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="291" height="178" alt="image" src="https://github.com/user-attachments/assets/bdeadcbd-0f87-49c1-a58d-512a502f0f5b" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="244" height="213" alt="image" src="https://github.com/user-attachments/assets/b11aa5bb-a44e-48eb-ad3d-50ee8f5c8975" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="227" height="202" alt="image" src="https://github.com/user-attachments/assets/2f6205ac-8674-45fc-a803-6e2e3377b94b" />

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="1906" height="66" alt="image" src="https://github.com/user-attachments/assets/64bda2ce-e448-4ccf-87cf-7120022a6314" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="251" height="71" alt="image" src="https://github.com/user-attachments/assets/4322bf0d-d881-4507-ae1b-12b4ba8b0e4f" />


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="269" height="398" alt="image" src="https://github.com/user-attachments/assets/9391fa76-0a9c-4321-b38c-25c60fc3aee5" />


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

<img width="232" height="50" alt="image" src="https://github.com/user-attachments/assets/87f88b10-cb2a-4cb7-afb0-e32e6bf13ba8" />


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

<img width="709" height="207" alt="image" src="https://github.com/user-attachments/assets/32848a61-feb4-424b-90dd-72981f9900d4" />

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="387" height="107" alt="image" src="https://github.com/user-attachments/assets/22a55583-e659-4d3c-9f14-452fdf6c98a0" />


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….


<img width="234" height="133" alt="image" src="https://github.com/user-attachments/assets/d4f2240a-228d-47b8-9223-fb404b70f4db" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="625" height="156" alt="image" src="https://github.com/user-attachments/assets/d5418822-3cd4-46cc-8467-cc67fbf1b53d" />


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

<img width="436" height="123" alt="image" src="https://github.com/user-attachments/assets/9f3f1510-8c51-4423-9d1a-deff72d0a10f" />

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="327" height="65" alt="image" src="https://github.com/user-attachments/assets/209c8925-e235-4ee3-9995-a52711150259" />


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="208" height="51" alt="Screenshot_2025-09-03_14-07-37" src="https://github.com/user-attachments/assets/8d61994c-27e3-4df1-8591-f37fe9dcfaa7" />


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

<img width="264" height="401" alt="image" src="https://github.com/user-attachments/assets/0ead90a9-4aa9-4ad0-a5a8-a2c37286c020" />

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="231" height="177" alt="image" src="https://github.com/user-attachments/assets/def1d141-822d-4f58-ba33-d6006d38600d" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="738" height="264" alt="image" src="https://github.com/user-attachments/assets/eae75b74-06f3-4de7-bb7b-27dc72682029" />


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

<img width="464" height="68" alt="image" src="https://github.com/user-attachments/assets/e9554295-7748-4449-8a68-6cc97bf620e3" />

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="748" height="220" alt="image" src="https://github.com/user-attachments/assets/4ed91859-a448-4a6a-b834-cb128528ed59" />


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="299" height="62" alt="image" src="https://github.com/user-attachments/assets/b3db5604-dd23-4c5a-8842-f05c274c76bb" />




















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
