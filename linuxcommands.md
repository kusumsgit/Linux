## Important commands and tricks

mkdir -p workspaces/{local,remote,dir1,dir2} : this will create a parent directory named workspace and inside it local,remote,dir1 and dir2 subdirectories
mkdir -p workspaces/local/remote/dir1 : This will create a parent directory named workspaces inside that local and inside local dir1
mkdir <dirname>
  
###   To make your terminal font bigger use ctrl shift +
  
  #### After making a directory to create a file you can either use touch command or nano or vm 
  
  vm editor: vm <filename> then press i to enter insert mode and :wq to save and exit and :q! to exit without saving your content.
  nano <filename> then ctrl x and write y and enter to exit out from nano.
  
  
### The tar command archives multiple files into a TAR file – a common Linux format similar to ZIP, with optional compression.

Here’s the basic syntax:

tar [options] [archive_file] [file or directory to be archived]

For instance, you want to create a new TAR archive named newarchive.tar in the /home/user/Documents directory:

tar -cvf newarchive.tar /home/user/Documents

The tar command accepts many options, such as:

-x extracts a file.
-t lists the content of a file.
-u archives and adds to an existing archive file.
  
 
### The ping command is one of the most used basic Linux commands for checking whether a network or a server is reachable. In addition, it is used to troubleshoot various connectivity issues.

Here’s the general format:

ping [option] [hostname_or_IP_address]

For example, you want to know whether you can connect to Google and measure its response time:

ping google.com
  
  
  
  




















