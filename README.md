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

#### output:
<img width="472" height="68" alt="1" src="https://github.com/user-attachments/assets/83ca5c16-2752-46f3-ae8e-7513cc5561a3" />


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

#### output:
<img width="278" height="67" alt="2" src="https://github.com/user-attachments/assets/7e88be7f-7ae9-43d6-bd9b-2b32362f319c" />


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

#### output:
<img width="371" height="107" alt="3" src="https://github.com/user-attachments/assets/5ceb1594-4a61-42d5-bf82-29c82882ee6a" />



### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

#### output:
<img width="458" height="168" alt="4" src="https://github.com/user-attachments/assets/ffd17320-b937-4ab5-91d2-b880aca531fc" />


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

#### output:
<img width="411" height="215" alt="5" src="https://github.com/user-attachments/assets/99626170-d385-45ab-b645-20bc2655c54e" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
#### output:
<img width="486" height="255" alt="6" src="https://github.com/user-attachments/assets/696af695-c7a7-4941-9ad9-a154852c113a" />

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

#### output:
<img width="376" height="221" alt="7" src="https://github.com/user-attachments/assets/17bee5e8-0cc8-42d5-89a5-18d6bf910810" />



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

#### output:
<img width="1157" height="295" alt="8" src="https://github.com/user-attachments/assets/6cc65953-cbfb-4b75-b5d0-967ebd9da42c" />


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

#### output:
<img width="590" height="127" alt="9" src="https://github.com/user-attachments/assets/7f4072a0-403e-4ca2-86b2-03f0abe3427d" />


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

#### output:

<img width="491" height="331" alt="10" src="https://github.com/user-attachments/assets/a203736d-f93c-4b83-abc1-dc7281dff3ad" />

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

#### output:
<img width="522" height="131" alt="11" src="https://github.com/user-attachments/assets/60ae0830-9d02-4298-94e4-85b84a936f72" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

#### output:
<img width="491" height="212" alt="12" src="https://github.com/user-attachments/assets/852ce4a0-7035-413a-b462-bf7b3334df78" />



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

#### output:

<img width="483" height="238" alt="13" src="https://github.com/user-attachments/assets/b50125c9-56fa-4779-b5e8-9d07e1de51dd" />

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

#### output:

<img width="950" height="95" alt="14" src="https://github.com/user-attachments/assets/38472443-ed2b-4142-be45-88c8153fe250" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

#### output:
<img width="347" height="75" alt="15" src="https://github.com/user-attachments/assets/f93a5833-0a3f-4671-9c4f-9c1669d7324d" />



### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

#### output:
<img width="502" height="63" alt="16" src="https://github.com/user-attachments/assets/21ca5e35-328e-4803-977b-c771816538b2" />


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

#### output:

<img width="600" height="195" alt="17" src="https://github.com/user-attachments/assets/feedd16c-ec8a-4647-af4d-e9015d9fbb0a" />

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

#### output:

 <img width="727" height="317" alt="18" src="https://github.com/user-attachments/assets/df1a4a2f-770a-470d-a9b0-c8bc1445c760" />

### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

#### output:
<img width="570" height="322" alt="19" src="https://github.com/user-attachments/assets/eadb7eb1-860f-4c1f-a499-72340e719c2f" />


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

#### output:

<img width="513" height="340" alt="20" src="https://github.com/user-attachments/assets/d4aec96f-5243-4e32-853e-41ce79eea03d" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

#### output:
<img width="767" height="413" alt="21" src="https://github.com/user-attachments/assets/6e6117a4-a7bd-4898-8211-5cf722224715" />


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

#### output:
<img width="593" height="272" alt="22" src="https://github.com/user-attachments/assets/982f8aa8-4b18-41a5-b29a-e49887509075" />

### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

#### output:
<img width="585" height="170" alt="23" src="https://github.com/user-attachments/assets/c6f5a697-2b2e-464f-a61b-c035085df181" />



### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
#### output:
<img width="867" height="171" alt="24" src="https://github.com/user-attachments/assets/ed676cd3-be3b-4229-b965-e0bec57e7b62" />


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

#### output:

<img width="548" height="408" alt="25" src="https://github.com/user-attachments/assets/488280b7-2238-4bda-90c5-da0db2f35b18" />

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

#### output:

<img width="396" height="227" alt="26" src="https://github.com/user-attachments/assets/efee5b29-f36c-4f9f-84af-992f18b3da45" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

#### output:

<img width="855" height="203" alt="27" src="https://github.com/user-attachments/assets/76c60f47-304f-42e7-9ad9-4c7db694fdf2" />

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

#### output:

 <img width="478" height="93" alt="28" src="https://github.com/user-attachments/assets/4eafe181-1817-42d2-b7ff-68aedb0feef3" />

### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

#### output:

<img width="766" height="275" alt="29" src="https://github.com/user-attachments/assets/c5e2b133-bdf9-4594-8ebf-b70b889caa72" />

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

#### output:

<img width="585" height="221" alt="30" src="https://github.com/user-attachments/assets/e8932549-1dfd-4369-a1c6-494e6d64a427" />





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
