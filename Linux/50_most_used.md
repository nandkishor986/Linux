1. `ls` : List files and Directories.

- `ls -ltr` : `-l` = "Long List", `-t` = "Sort by time i.e Newest First", `-r` = "Reverse order while sorting"

2. `pwd` : "Print current working directory i.e print the directory or folder in which we are working currently."

3. `cd` : "Change directory i.e Navigate through directories."

4. `mkdir` : "Make directory - Create directories in liniux."

5. `mv` : "Move or rename files or folders in linux." - Cut / Paste.

- `mv file1.txt file2.txt` -+> Rename file1.txt to file2.txt.

- `mv file1.txt ../project` -+> Move file1.txt into project directory.

- `mv project projects` -+> Rename project directory to projects.

6. `cp` : "Copy files in linux."

- `cp file1.txt ../Backdrops` -+> "Copy file1.txt to Backdrops directory." - Copy / Paste.

7. `rm` : "Delete files or directories."

- `rm -rf file1.txt` -+> `-f` - "Forcefully remove i.e ignore nonexistent files & arguments, never prompt", `-r` - "remove directories and their contents recursively."

8. `ssh-keygen` : "Generate a pair of public and private keys."

9. `rmdir` : "Remove directories."

10. `touch` : "Create blank or empty files."

11. `ln` : "Create symbolic links i.e shortcuts to other files."

* Hard Link: Hard Link is a direct pointer to the data on the disk. Multiple hard links can exist for the same file and they are indistinguishable from the original file. The data will be present as it is in the hard link if the original file is deleted. 

- `ln files1.txt ../project/devops.txt` - `ln original_file.txt hard_link.txt`.

* Soft Link or Symbolic link: Symbolic link is a pointer to the another file or directory. It is like a shortcut. If the original file is deleted, the symbolic link will be broken and won't point to any data. 

# Note: First create a file and then create a soft link. Do not create soft link first and then create a file. It will crate a broken soft link this way. 

- `ln -s original_file.txt soft_link.txt`

12. `cat` : "Display file contents on the terminal."

13. `clear` : "Clear the terminal display."

14. `echo` : "Print any text on the termianal."

15. `less` : "Linux command to display paged outputs in the termianal."

16. `man` : "Access manual pages for all Linux Commands."

17. `uname` : "Display basic information about the operating system like kernel name, network node name, kernel release, kernel version, machine hardware name etc."

18. `whoami` : "Get the active username."

19. `tar` : "Extract and Compress files in linux."

- `tar -czvf bzip_files.tar.gz file1.txt file2.txt.` -+> "Compress the files into bzip_files.tar.gz zip files."

- `tar -xvf bzip_files.tar.gz` -+> "Extract the files - file1.txt & file2.txt from the bzip_files.tar.gz file."

20. `grep` : "Search for a string or pattern within an output."

21. `head` : Display 10 lines from the top when used without `-n` option. 

- `head -n 5 file1.txt` : "Return specified no. of lines from the top."

22. `tail` : "Display 10 lines from the bottom when used without `-n` option."

- `tail -n 5 file1.txt` : "Return specified no. of lines from the bottom."

- `tail -f access.log` : "Output appended data as the file grows. Mostly used while viewing log files."

23. `diff` : "Find the difference between two files."

24. `cmp` : "Compare 2 files byte by byte, it allows us to check if two files are identical." 

25. `comm` : "Combines the functionality of `diff` and `cmp` i.e compare two sorted files line by line."

26. `sort` : "Sort the content of the file while outputing."

27. `export` : "Export environment variables in linux."

28. `zip` : "Zip files in Linux."

29. `unzip` : "Unzip files in linux."

30. `ssh` : "Secure Shell Login or Secure Shell Command."

31. `ps` : "Display active processes."

32. `kill and killall` : "Kill active processes by process ID or name."

33. `df` : "Display disk file system information."

34. `mount` : "Mount file systems in linux."

35. `chmod` : "Command to change file permissions."

36. `chown` : "Grant ownership of files or folders to users."

37. `ifconfig` : "Display network interfaces and IP addresses."

38. `traceroute` : "Trace all the network hops to reach the destination."

39. `wget` : "Direct download files from the internet."

40. `ufw` : "Firewall command used to allow or deny traffic coming from some protocols inside a machine."

41. `iptables` : "Base firewall for all other firewall utilities to interface with."

42. `apt, packman, yum, rpm` : "Package Managers depending on the distributions."

43. `sudo` : "Super user do - Command used to escalate privileges in Linux."

44. `cal` : "Display a command-line calendar."

45. `alias` : "Create custom shortcuts for regularly used commands."

46. `dd` : "Create bootable USB disks."

47. `whereis` : "Locate the binary, source and manual pages for a command."

48. `whatis` : "Find out for what a particular command is used for."

49. `top` : "View active processes live with their system usage."

50. `useradd` : "Add a new user."

51. `usermod` : "Change existing users data."

52. `passwd` : "Create or Update passwords for existing users."

53. `yum install [package_name]` : "Install a package using yum."

54. `yum remove` : "Remove a package using yum."

55. `yum update` : "Update all installed packages."

56. `yum search [keyword]` : "Search for packages containing a specific keyword."