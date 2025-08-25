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

Got it 👍 You want a **similar style list of 25 basic Windows commands** (like you did for Linux).
Here’s a well-structured version for **Windows CMD (Command Prompt)** that beginners and advanced users can use.

---

# 25 Essential Windows Commands

These commands are widely used for Windows system administration, file management, and troubleshooting.
Perfect for beginners and power users alike.

---

### 1) **dir Command**

The `dir` command displays a list of files and directories in the current folder.

**Syntax:**

```cmd
dir
```
<img width="748" height="368" alt="image" src="https://github.com/user-attachments/assets/32dba479-e9bf-4805-bd6e-85a5e859237c" />

---

### 2) **cd Command**

The `cd` command is used to change the current working directory.

**Syntax:**

```cmd
cd foldername
```
<img width="753" height="61" alt="image" src="https://github.com/user-attachments/assets/b93bcbcc-cc77-4f9c-b22d-d8a153433e23" />

---

### 3) **cls Command**

The `cls` command clears the terminal (Command Prompt) screen.

**Syntax:**

```cmd
cls
```

<img width="801" height="477" alt="image" src="https://github.com/user-attachments/assets/2f087e3a-cd87-4bd0-a791-1fef186212de" />
<br>
<img width="784" height="111" alt="image" src="https://github.com/user-attachments/assets/137a4750-7e31-49b9-ae50-0097e895e511" />

---

### 4) **mkdir Command**

The `mkdir` command is used to create a new directory.

**Syntax:**

```cmd
mkdir foldername
```
<img width="831" height="287" alt="image" src="https://github.com/user-attachments/assets/0fe1903c-b079-4750-93ba-4833a14f4c9d" />

---

### 5) **rmdir Command**

The `rmdir` command deletes a directory (only if it is empty).

**Syntax:**

```cmd
rmdir foldername
```
<img width="848" height="268" alt="image" src="https://github.com/user-attachments/assets/af9ec6d1-746d-478c-b6f6-beb848705663" />

---

### 6) **del Command**

The `del` command deletes one or more files.

**Syntax:**

```cmd
del filename.txt
```
<img width="848" height="93" alt="image" src="https://github.com/user-attachments/assets/b345ce00-4a36-4f9c-8d2b-cda58ef1f186" />

---

### 7) **copy Command**

The `copy` command copies files from one location to another.

**Syntax:**

```cmd
copy file1.txt D:\backup\
```
<img width="1125" height="244" alt="image" src="https://github.com/user-attachments/assets/1b4f3580-2f39-4847-bcb8-7d31d4c19629" />

---

### 8) **move Command**

The `move` command moves files from one directory to another.

**Syntax:**

```cmd
move file.txt D:\newfolder\
```
<img width="1203" height="59" alt="image" src="https://github.com/user-attachments/assets/224bb5ab-60b0-4449-9b20-9136ccfa4858" />

---

### 9) **rename Command**

The `rename` command is used to rename a file.

**Syntax:**

```cmd
rename oldname.txt newname.txt
```
<img width="1079" height="270" alt="image" src="https://github.com/user-attachments/assets/44b5e16b-c18c-45c5-ae07-4cb6879a8dda" />

---

### 10) **type Command**

The `type` command displays the contents of a text file.

**Syntax:**

```cmd
type filename.txt
```
<img width="871" height="166" alt="image" src="https://github.com/user-attachments/assets/036fd021-4308-4bd3-97dc-556e055d8b77" />

---

### 11) **echo Command**

The `echo` command displays messages or turns command echoing on/off.

**Syntax:**

```cmd
echo Hello, World!
```
<img width="883" height="115" alt="image" src="https://github.com/user-attachments/assets/6f6070c2-558f-4e56-8c15-8f8d5981b993" />

---

### 12) **exit Command**

The `exit` command closes the Command Prompt window.

**Syntax:**

```cmd
exit
```
<img width="887" height="479" alt="image" src="https://github.com/user-attachments/assets/480f30a9-727b-4e09-978a-a905b15be856" />

<img width="856" height="166" alt="image" src="https://github.com/user-attachments/assets/e167baed-7db7-4337-ae25-19d0372c9a7f" />

---

### 13) **tasklist Command**

The `tasklist` command shows all currently running processes.

**Syntax:**

```cmd
tasklist
```
<img width="770" height="443" alt="image" src="https://github.com/user-attachments/assets/3788ffad-5f44-4adb-aee8-1e68f79d8938" />

---

### 14) **taskkill Command**

The `taskkill` command terminates a running process.

**Syntax:**

```cmd
taskkill /IM notepad.exe /F
```
<img width="884" height="75" alt="image" src="https://github.com/user-attachments/assets/4292f979-5456-4e81-94dc-7410a38c2f90" />

---

### 15) **ipconfig Command**

The `ipconfig` command displays the computer’s network configuration (IP address, subnet mask, gateway, etc.).

**Syntax:**

```cmd
ipconfig
```
<img width="714" height="371" alt="image" src="https://github.com/user-attachments/assets/397fa886-2b48-4a55-b9f1-1872446389a4" />

---

### 16) **ping Command**

The `ping` command checks network connectivity to a website or IP address.

**Syntax:**

```cmd
ping google.com
```
<img width="783" height="302" alt="image" src="https://github.com/user-attachments/assets/b4e1933a-60b8-419e-82cc-3c2b3ae7befd" />

---

### 17) **netstat Command**

The `netstat` command shows active network connections and ports.

**Syntax:**

```cmd
netstat
```
<img width="712" height="230" alt="image" src="https://github.com/user-attachments/assets/f2c85cd3-8f03-44b5-8e2a-bb8a4c2b32ca" />

---

### 18) **systeminfo Command**

The `systeminfo` command displays detailed system information like OS version, RAM, and processor.

**Syntax:**

```cmd
systeminfo
```
<img width="717" height="372" alt="image" src="https://github.com/user-attachments/assets/a3d99e4d-0df8-42db-9ba6-5504a62b8cb4" />

---

### 19) **chkdsk Command**

The `chkdsk` command checks the file system and disk for errors.

**Syntax:**

```cmd
chkdsk C:
```
<img width="715" height="215" alt="image" src="https://github.com/user-attachments/assets/e65aba77-8cc4-41b4-8d0a-f577f2410b23" />


---

### 20) **sfc Command**

The `sfc` command scans and repairs corrupted system files.

**Syntax:**

```cmd
sfc /scannow
```
<img width="728" height="203" alt="image" src="https://github.com/user-attachments/assets/8f7f9255-7b79-4c99-9453-a63017b8d4dd" />

---

### 21) **shutdown Command**

The `shutdown` command shuts down or restarts the computer.

**Syntax:**

```cmd
shutdown /s   (Shutdown)  
shutdown /r   (Restart)
```
<img width="244" height="72" alt="image" src="https://github.com/user-attachments/assets/5257e8c7-2884-4678-bbd4-3726a67084fa" />

---

### 22) **whoami Command**

The `whoami` command displays the current logged-in user.

**Syntax:**

```cmd
whoami
```
<img width="696" height="73" alt="image" src="https://github.com/user-attachments/assets/bb5226f1-d175-4444-ba04-43cbe2ef87b6" />

---

### 23) **hostname Command**

The `hostname` command displays the computer’s hostname.

**Syntax:**

```cmd
hostname
```
<img width="709" height="67" alt="image" src="https://github.com/user-attachments/assets/c94d281d-c593-4c14-8074-582fd7c63772" />

---

### 24) **date & time Command**

The `date` and `time` commands are used to display or set the system date and time.

**Syntax:**

```cmd
date
time
```
<img width="672" height="88" alt="image" src="https://github.com/user-attachments/assets/add59f7d-754a-44c0-b76e-9ff2584461dc" />

---

### 25) **help Command**

The `help` command lists all available commands in Windows CMD.

**Syntax:**

```cmd
help
```
<img width="724" height="321" alt="image" src="https://github.com/user-attachments/assets/adab65c7-d575-4919-ba74-2efbad64a56c" />



## Conclusion 

These 25 Linux and 25 Windows commands build a strong foundation in navigation, file management, system information, networking, and troubleshooting across both operating systems.
