# Ex-01-Linux-Commands
## Name: BASKAR J


## Reg no:212223040025


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

![376898358-6f98b604-caaf-40d7-b684-b31beba592d3](https://github.com/user-attachments/assets/522d7a0b-63bc-4309-86b6-35b81d3f84f6)


 Syntax: ls


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![376898379-0d574161-ceb3-46d0-98b9-a13d957e638e](https://github.com/user-attachments/assets/251b8886-5fbe-4769-8dfb-b016793d59b3)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![376898396-eca27f67-3a93-4122-9a3e-ad921a0f7d09](https://github.com/user-attachments/assets/1533d303-e208-4425-b3f5-98d03f3eea3b)

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![376898407-95092d16-d23d-4bf7-811a-c74c97d1041f](https://github.com/user-attachments/assets/2d59fae9-429d-4fd1-818c-9797add3d12b)

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
![376898424-20a08b36-115b-4667-ac49-68e0de404d35](https://github.com/user-attachments/assets/5610b7ee-7ebc-40cf-8775-5c2c19d4316d)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![376898456-a68cced8-bdb3-4b96-96d0-ae138067aef1](https://github.com/user-attachments/assets/1e3750eb-1d61-4a88-ab61-1adb1a378b2a)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>


![376898481-437fcf90-67d2-4b53-9e0b-34c59126ac1a](https://github.com/user-attachments/assets/1bf49df2-827a-4be2-b9b0-1215f3e356d2)

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![376898504-3d4f580e-f711-47e1-9f86-d348a03b1374](https://github.com/user-attachments/assets/bc36ea88-d229-448b-851a-b2ae472b6278)

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![376898539-a701d9b5-8755-4860-b595-c90cf63ed58c](https://github.com/user-attachments/assets/4bd53c47-91d4-42b5-84f9-37eb98352b68)

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
![376898570-3d82da66-f19d-45e7-a7c6-ba051f8ea232](https://github.com/user-attachments/assets/40cc82cd-ef4f-4f9d-9eb7-ca3b4cf390f6)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
![376898586-352862aa-cfc0-4119-b699-2710619741af](https://github.com/user-attachments/assets/aa3f603d-f3dc-484e-bd65-9a43c3e2830c)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![376898595-5f504f33-5591-4193-bdde-2bdffbce16dd](https://github.com/user-attachments/assets/a939564f-8fb5-4e83-9c57-1525e121fadf)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
![376898608-8c7c902c-261d-471e-91d8-398d29b68421](https://github.com/user-attachments/assets/809563f3-dad1-49c5-890e-549a6ab8ad36)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![376898622-2b5505b0-414f-4634-9b24-76cbe180a2f3](https://github.com/user-attachments/assets/117d794c-a422-4c02-9154-278df9eb3f1b)

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
![376898637-7ac56c1a-1fca-44ce-9a97-ee2f1316bd11](https://github.com/user-attachments/assets/80888461-e401-4bca-894d-10b790446bf9)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
![376898660-d1b279a2-0289-459a-aa9e-5a1d454593fa](https://github.com/user-attachments/assets/a7a47330-5dd2-47b0-82a1-b687b04dee09)

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
![376898688-1918c386-2b27-47a2-93e4-a4da4516d36f](https://github.com/user-attachments/assets/c5bcc1cf-70a9-4580-b2a1-6004087b70e4)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
![376898709-781d6009-7070-43a6-bd4e-e16f141219b3](https://github.com/user-attachments/assets/b86e60e1-7579-49d6-8adc-3cabd358a17d)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
![376898727-c947fdcf-d906-4052-bf91-943598478282](https://github.com/user-attachments/assets/dad11b5a-f56b-4f09-bb0e-56c12dcfc0f6)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
![376898751-06913a7c-cd27-4107-a73f-7f1bbfaec252](https://github.com/user-attachments/assets/89fe94ed-7ad2-401c-9f2d-e383b1b842cc)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![376898771-80e66b4c-9dca-4d04-a4dc-209114526baa](https://github.com/user-attachments/assets/a5b514d1-4b84-49c9-ad0a-bd7cf5fb2081)

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
![376898796-5d14e282-3d91-4930-a0b4-49665be282f4](https://github.com/user-attachments/assets/be6e8fe4-16b5-4200-94fc-7ae2fa2b83cb)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![376898816-17358982-cead-4f94-8cce-3be4605eda32](https://github.com/user-attachments/assets/5a3582cf-8a63-44be-8aa5-dd0d3ca06ea1)

### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![376898835-e265b0c7-92f8-429c-b66f-ccaaf5396da8](https://github.com/user-attachments/assets/066c4136-0cd5-48c9-ab33-ba694a65f3fd)

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 ![376898860-6799494a-8c39-4956-b781-4a95ec6f1e12](https://github.com/user-attachments/assets/1e923df7-92a2-47e7-8150-933b8d32bd34)

### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
![376898891-526f8f4f-0b4d-4017-8c29-94a1cfa230e0](https://github.com/user-attachments/assets/e54a4583-3a46-4922-ae27-6698261d6786)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
