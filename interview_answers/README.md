19Q: Say that I opened my browser and went to www.google.com. Describe what exactly happens in order for the page to display in my browser?

19A: Your browser initiates a DNS lookup to find the IP address of www.google.com then sends an HTTP request to Google's server. The server then responds with the HTML, CSS, and JavaScript of the page. Your browser then renders the page content, making additional requests for objects like images and executing JavaScript code.

20Q: What is an inode? What metadata does it contain?

20A: An inode is a data structure on a filesystem on Unix-like systems. It stores information about a filesystem object but does not contain the data itself or the filename. Metadata in an inode includes the file size, device ID, user ID, group ID, file mode, timestamps, and link count.

21Q: What is the difference between a hard link and a soft link (symlink)?

21A: A hard link is a direct reference to the file's inode, acting indistinguishably from the file itself. A symlink is a pointer to a file name; it's a separate file that redirects to another file or directory.

22Q: What is the Windows registry? How does linux do the same thing? Mac?

22A: The Windows Registry is a database storing low-level settings for the OS and applications. Linux uses configuration files (often found in /etc) and directories for this purpose. macOS utilizes both configuration files and a database similar to the Registry called plist files.

23Q: What is the bootup process of a machine of your choice?

23A: For a Linux machine, the boot process typically involves the BIOS/UEFI initializing hardware, then booting from a storage device. It loads the bootloader (like GRUB) which then loads the kernel. The kernel initializes the system and starts the init process, which brings up the system in user-space.
