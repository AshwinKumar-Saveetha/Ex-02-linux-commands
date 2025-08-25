# Workshop2-linux-commands
# LINUX-BASIC-COMMANDS
# 25 Essential Linux Commands

These commands are widely used for Linux system administration, file management, and navigation.  
Perfect for beginners and advanced users alike.



### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

<img width="786" height="95" alt="Screenshot 2025-08-25 083039" src="https://github.com/user-attachments/assets/02bf62c2-c948-4347-a459-d5a99fc25fcb" />

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="187" height="81" alt="Screenshot 2025-08-25 083048" src="https://github.com/user-attachments/assets/9caed99a-69f8-492c-a0ac-efa7654c0539" />

### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="860" height="118" alt="Screenshot 2025-08-25 083259" src="https://github.com/user-attachments/assets/63e87d5e-a810-4b1b-958d-49280ac81d49" />

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="786" height="134" alt="Screenshot 2025-08-25 083320" src="https://github.com/user-attachments/assets/b5312fd8-dae0-4000-ac75-5ccd39f934df" />

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="256" height="148" alt="image" src="https://github.com/user-attachments/assets/c6a5f4e7-1c0a-4efa-9f57-bd74d63476d4" />

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="243" height="90" alt="image" src="https://github.com/user-attachments/assets/8281a04c-4004-49b8-bd23-d83bb15c08c7" />
<br>
<img width="252" height="97" alt="image" src="https://github.com/user-attachments/assets/f6290e0a-a029-4da5-b9fb-c66fe87a6f79" />

### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="253" height="142" alt="image" src="https://github.com/user-attachments/assets/ee168117-6988-4aaf-bda8-6bb75ba0ad7a" />

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="261" height="56" alt="image" src="https://github.com/user-attachments/assets/20ac0a42-daf9-4824-9062-1eacdedda629" />

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="207" height="93" alt="image" src="https://github.com/user-attachments/assets/d2b0279d-d941-41c0-a8bb-567bb7263a1e" />

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

<img width="252" height="292" alt="image" src="https://github.com/user-attachments/assets/7b599f7e-3436-4396-9822-71eecb742321" />
 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="283" height="172" alt="image" src="https://github.com/user-attachments/assets/7c776031-bf02-413d-9b09-55acafc330d0" />

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="270" height="235" alt="image" src="https://github.com/user-attachments/assets/f86afa6a-9463-41e0-87e3-9cbc094043ca" />

### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="246" height="236" alt="image" src="https://github.com/user-attachments/assets/b212e7fe-531d-418c-9b00-be74742488b7" />

### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="906" height="117" alt="image" src="https://github.com/user-attachments/assets/4fcb5103-a5d9-4872-8b2b-c5673a1e5ccb" />

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="271" height="141" alt="image" src="https://github.com/user-attachments/assets/f425d162-49ba-448a-9ea0-daa226714aa2" />

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="286" height="358" alt="image" src="https://github.com/user-attachments/assets/53641e35-21a3-4f29-971c-112efb838a2e" />

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

<img width="425" height="132" alt="image" src="https://github.com/user-attachments/assets/d6292af1-5787-49a9-80d8-bd2124c7e5e3" />

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

<img width="260" height="177" alt="image" src="https://github.com/user-attachments/assets/3dc77307-151c-4e69-9d56-a8671256b296" />                                                                                                                                           

### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="392" height="127" alt="image" src="https://github.com/user-attachments/assets/ac46ec60-1096-4e82-9e08-3692a3902bdf" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="255" height="91" alt="image" src="https://github.com/user-attachments/assets/a49c1a53-a0e1-4a6c-afdc-895717badb34" />

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="707" height="123" alt="image" src="https://github.com/user-attachments/assets/80e2b348-5a6f-45d1-9382-09d018048aa0" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

<img width="425" height="132" alt="Screenshot 2025-08-25 085520" src="https://github.com/user-attachments/assets/4c2ab2ff-62b1-4f44-bb0b-f4b37e0c754e" />

### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="447" height="125" alt="image" src="https://github.com/user-attachments/assets/c793c286-ba90-40d9-8257-2fd17bceb3de" />

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="622" height="192" alt="image" src="https://github.com/user-attachments/assets/b1dcd2de-bcd9-4966-9f7d-62079fd09b58" />

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

<img width="248" height="362" alt="image" src="https://github.com/user-attachments/assets/90f685d5-9994-4bba-8eaa-915235ffaac6" />

### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="245" height="196" alt="image" src="https://github.com/user-attachments/assets/31454f22-9307-4f55-9828-f64d9b011ee3" />

### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="696" height="481" alt="image" src="https://github.com/user-attachments/assets/2a63de76-5485-4242-b8a4-be523ce65372" />
<br>
<img width="257" height="93" alt="image" src="https://github.com/user-attachments/assets/1cd0d12e-e2cc-424f-9061-dc9d4be795f3" />

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

<img width="633" height="82" alt="image" src="https://github.com/user-attachments/assets/cc9c1979-ab75-4bb2-874a-e05b4bfac8b1" />
 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="747" height="235" alt="image" src="https://github.com/user-attachments/assets/b315f999-38ba-40ec-9f95-070d91d04deb" />

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="218" height="67" alt="image" src="https://github.com/user-attachments/assets/b9e7eeff-2d1c-4cd2-b762-474d3d31346a" />



## Conclusion 
These 25 essential Linux commands cover the most common tasks we’ll see while working in a terminal — from navigation (ls, cd, pwd) and file management (cp, mv, rm, touch) to text viewing/editing (cat, nano, less) and system information (df, du, history).
