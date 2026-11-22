# 19CS416-CS-Ex-3-Linux-Commands

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**
<img width="165" height="56" alt="image" src="https://github.com/user-attachments/assets/89fab13f-28bb-4ac5-a325-669cf4876543" />



### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**
<img width="317" height="50" alt="image" src="https://github.com/user-attachments/assets/62484feb-01c2-43d9-86e0-5c6123c8596a" />


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**
<img width="435" height="72" alt="image" src="https://github.com/user-attachments/assets/5cf8bc7e-6251-426c-9292-e3665904d587" />


### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**
<img width="555" height="100" alt="image" src="https://github.com/user-attachments/assets/9a590609-9626-4171-8a43-f01adaa4cb16" />


### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**
<img width="500" height="77" alt="image" src="https://github.com/user-attachments/assets/afb54b67-d3bd-491a-86ff-337ad56a2b41" />


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**
<img width="246" height="110" alt="image" src="https://github.com/user-attachments/assets/b078c137-d1d0-4a96-a4c4-f8f017f0c029" />


### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**
<img width="346" height="42" alt="image" src="https://github.com/user-attachments/assets/dbb7e142-8f57-4f4a-bf6c-32c080261146" />


### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**
<img width="346" height="42" alt="image" src="https://github.com/user-attachments/assets/cb4d2ae9-7589-4a0e-a32e-4cd37b6f57b4" />


### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**
<img width="268" height="55" alt="image" src="https://github.com/user-attachments/assets/c5e6bb06-7538-405a-86da-803847afea77" />


### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**
<img width="317" height="52" alt="image" src="https://github.com/user-attachments/assets/a3f05d13-0ff7-488f-af0f-85c41ac8e23f" />


### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**
<img width="317" height="52" alt="image" src="https://github.com/user-attachments/assets/4ff73ca7-3bbb-4128-a09e-542e2f61d424" />


### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**
<img width="276" height="61" alt="image" src="https://github.com/user-attachments/assets/edab75df-3cd3-492d-aa90-6fcec228d963" />


### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**
<img width="316" height="65" alt="image" src="https://github.com/user-attachments/assets/8c4ccabb-a0da-4fc2-a4d7-6e79e3b18cd4" />


### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**
<img width="316" height="65" alt="image" src="https://github.com/user-attachments/assets/9f91d9cf-f4d1-4722-bff4-415e32d65857" />


### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**
<img width="932" height="77" alt="image" src="https://github.com/user-attachments/assets/5ec5034b-32d7-4d51-8fd7-bd52dc94db0d" />


### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**
<img width="316" height="65" alt="image" src="https://github.com/user-attachments/assets/b13e9ea4-4637-4fce-a26a-d1a91b2dd730" />


### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**
<img width="197" height="38" alt="image" src="https://github.com/user-attachments/assets/c1d8b18d-87a3-4ec2-816a-8907e812a70b" />


### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**
<img width="375" height="87" alt="image" src="https://github.com/user-attachments/assets/3f1bfa1b-41f0-4226-8a29-15de3961dd2a" />


### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**
<img width="352" height="61" alt="image" src="https://github.com/user-attachments/assets/6429e424-88e4-4844-a6e6-e3a2f347d264" />


### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**
<img width="352" height="61" alt="image" src="https://github.com/user-attachments/assets/652fceae-586c-4071-9491-004f06cf5135" />


### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**
<img width="650" height="90" alt="image" src="https://github.com/user-attachments/assets/64694979-a54c-4d4e-800c-01f2de327344" />


### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**
<img width="650" height="90" alt="image" src="https://github.com/user-attachments/assets/6b95ceba-5bff-4e9a-ae1c-cd1b1b43bd6b" />


### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**
<img width="650" height="90" alt="image" src="https://github.com/user-attachments/assets/10a4150a-b689-4b15-b280-0c19acf50f44" />


### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**
<img width="320" height="31" alt="image" src="https://github.com/user-attachments/assets/22432b97-0e54-4d36-a9aa-c463f30195f0" />


### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**
<img width="531" height="125" alt="image" src="https://github.com/user-attachments/assets/df5a2464-a4a6-436d-9b41-fc0fa12c3e65" />


### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**
<img width="323" height="175" alt="image" src="https://github.com/user-attachments/assets/43d80027-ee7f-4c5e-9914-10be23863518" />


### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**
<img width="147" height="26" alt="image" src="https://github.com/user-attachments/assets/ad4e9ead-1696-4108-96cf-95f5a93a0cb7" />


### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**
<img width="147" height="26" alt="image" src="https://github.com/user-attachments/assets/ddd6bfbd-2a69-4089-b419-adb32032a7dd" />


### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**
<img width="548" height="90" alt="image" src="https://github.com/user-attachments/assets/762d0b92-773b-4a10-9a15-b482cbebb438" />


### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**
<img width="310" height="82" alt="image" src="https://github.com/user-attachments/assets/2143f378-32a6-42f8-81ec-81684f338a2e" />


## Result
Thus the given linux commands has been executed successully.
