# Bash Commands

## System Operations

	uname -a						Show system and kernel
	uptime							Show uptime
	whoami							Show username
	head -n1 /etc/issue					Show distribution
	env 							Show environment variables
	
## File commands

   	ls							List directory
	ls -al							Formatted listing with hidden files
	ls -lrt							Formatted listing sorted by newest bottom
	pwd							Show current directory
	mkdir dir						Create directory dir
	rm file							Delete file
	rmdir dir						Delete directory dir
	rm -rf dir						Delete all contents recursively on dir
	cp file1 file2						Copy file1 to file2
	cp -R dir1 dir2						Copy directory dir1 and subfolders to dir2
	mv file1 file2						Rename or move file1 to file2 if file2 is an existing directory, moves file1 into directory file2
	ln -s file link						Create symbolic link to file
	touch file						Create file
	more file						Output contents of file
	head file						Output first 10 lines of file
	head -100 file						Output first 100 lines of file
	tail file						Output last 10 lines of file
	tail -f file						Output file contents in real time as it is written

## Process management
	ps							Show current active processes
	top							Show running processes
	kill pid						Kill process pid


	
