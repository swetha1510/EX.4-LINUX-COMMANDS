# OS EX.4-LINUX-COMMANDS

# AIM:
To study and execute the basis of UNIX commands.

# COMMAND1:List Files and Directories
```
Syntax: 
	ls [options] [directory]
Code: 
	ls -l /home/user
Output: 
	List of files and directories in /home/user with details.
```
## Command 2 :cd - Change Directory
```
Syntax: 
	cd [directory]
Code: 
	cd /var/www
Output: 
	Change to the /var/www directory.
```

 ## Command 3 : pwd - Print Working Directory
 ```
 Syntax: 
	pwd
Code: 
	pwd
Output: 
	/home/user (prints the current working directory).
```

## Command 4 : touch - Create Empty File
```
Syntax: 
	touch [filename]
Code: 
	touch newfile.txt
Output: 
	Creates a new empty file named newfile.txt.
```

## Command 5 : mkdir - Create Directory
```
Syntax: 
	mkdir [directory]
Code: 
	mkdir my_directory
Output:	
	Creates a new directory named my_directory.
```
## command 6 : rm - Remove Files and Directories
```
Syntax: 
	rm [options] [file/directory]
Code: 
	rm file.txt
Output: 
	Deletes file.txt.
```
## Command 7 : cp - Copy Files and Directories
```
Syntax: 
	cp [options] source destination
Code: 
	cp file.txt /backup/
Output: 
	Copies file.txt to the /backup/ directory.
```

 ## Command 7 : mv - Move/Rename Files and Directories
 ```
Syntax: 
	mv [options] source destination
Code: 
	mv oldfile.txt newfile.txt
Output: 
	Renames oldfile.txt to newfile.txt.
 ```
 ## Command 8 : more - View File Content Page by Page
 ```
Syntax: 
	more [filename]
Code: 
	more longfile.txt
Output: 
	Allows you to view the content of longfile.txt one page at a time.
```

 ## Command 9 : rm - Remove Files and Directories
 ```
Syntax: 
	rm [options] [file/directory]
Code: 
	rm file.txt
Output: 
	Deletes file.txt.
```
 
 ## Command 10 : cat - Concatenate and Display File Content
 ```
Syntax: 
	cat [filename]
Code: 
	cat file.txt
Output: 
	Displays the content of file.txt.
```

 ## Command 11 : head - Display Top Lines of a File`
 ```
Syntax: 
	head [options] [filename]
Code: 
	head -n 5 file.txt
Output: 
	Shows the first 5 lines of file.txt.
```

 ## Command 12 : less - View File Content with Navigation
 ```
Syntax: 
	less [filename]
Code: 
	less largefile.txt
Output: 
	Displays largefile.txt with navigation capabilities.
```

 ## Command 13 : find - Search for Files and Directories
 ```
Syntax:
	find [path] [expression]
Code: 
	find /home/user -name '*.txt'
Output: 
	Finds all .txt files under /home/user.
```
 ## Command 14 : tail - Display Bottom Lines of a File
 ```
Syntax: 
	tail [options] [filename]
Code: 
	tail -n 10 file.log
Output: 
	Shows the last 10 lines of file.log.
```

 ## Command 15 : grep - Search Text in Files
 ```
Syntax: 
	grep [options] 'pattern' [file(s)]
Code: 
	grep 'keyword' file.txt
Output: 
	Lists lines containing 'keyword' in file.txt.
```
 ## Command 16 : chown - Change File Ownership
 ```
Syntax: 
	chown [options] user:group file(s)
Code: 
	chown user:group file.txt
Output: 
	Changes the owner and group of file.txt.
```
 ## Command 17 : tar - Archive and Compress Files
 ```
Syntax: 
	tar [options] [file(s)]
Code: 
	tar -cvzf archive.tar.gz dir/
Output: 
	Creates a compressed archive of the dir/ directory.
```
 ## Command 18 : chmod - Change File Permissions
 ```
Syntax: 
	chmod [options] permissions file(s)
Code: 
	chmod 644 file.txt
Output: 
	Sets read and write permissions for the owner and read-only permissions for others on file.txt.
```
 ## Command 19 : du - Display Directory Space Usage
 ```
Syntax: 
	du [options] [directory]
Code: 
	du -sh /var
Output: 
	Displays the total size of the /var directory in a human-readable format.
```
 ## Command 20 : df - Display Disk Space Usage
 ```
Syntax: 
	df [options] [filesystem(s)]
Code: 
	df -h
Output: 
	Shows disk space usage in a human-readable format.
 ```
# RESULT:
Thus basis of UNIX commands are studied and executed.
