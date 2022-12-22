  # Further on Linux 
## Linux file Hierarchy
 •Linux system files appear under the root directory(/).
  
  ## File structure in detail
  ### 1, /(root)
 •Every single file and directory starts from the root directory.
   ✓ the only root user has the right to write under this directory.

  ### 2, bin - Binary executables
 •Essential command binaries that need to be available in single 
   user mode for all users.

  ### 3, /boot - Boot loader files
 •Kernel intrd,vmlinux,grub files are located under/boot.
 
  ### 4, /dev - Essential device files
 •these include terminal devices ,USB,or any device attached 
   to the system.
 
  ### 5, /etc - et cetera
 •Contains configuration files required by all programs this also
   contains startup and shutdown shell scripts used to start/stop
   individual programs.

  ### 6, /home - Home directory
 •for all users to store their personal files.
 
  ### 7, /lib - Libraries
 •essential for the binaries in /bin & /sbin 
   Library filenames are either id lib "so"

  ### 8, /media - mount
• points for removable media such as CD-ROMs.
• temporary mount directory for removable devices.
 
  ### 9, /mnt - temporarily mounted file
 • temporary mount directory where sysadmins can mount filesystems.

  ### 10, /opt - optional application software packages
 • contains add on applications from individual vendors 

  ### 11, /sbin - Essential system binaries
 • the linux commands located under this directory are used typically
    by system administrator.
   ####  ✓ /sbin takes sudo before command 

  ### 12, /tmp - Temporary files
 • Files under this directory are deleted when system is rebooted.

  ### 13, /user - User Utilities
 • Contains binaries, Libraries, documentation and source code
    for second level programs.
 
   ## Text Editors
 #### Linux command line text Editors
     ✓ VM
     ✓ Nano
     ✓ Emacs
     ✓ Neovim ...
 #### Linux graphical text Editors
     ✓ Sublime
     ✓ Vs Code
     ✓ Gedit
     ✓ Pluma ...
 
    ### VIM
 • a very power full
 °it have tow modes
  1, command mode - you can do commands
  2, input mode - you can write
• Vim is by default on command mode
• When you open to get on insert mode you have to type "I"
• To back to command "ESC"
    ✓ save   :w
    ✓ Quite  :q
    ✓ Execute command  :%!
 
  ### Nano
•That usually comes pre installed in modern Linux systems.
  To startnano
    ✓ Nano filename
   The ^ is equal to "Ctrl"
• You can append texts from other files with
    ✓ Ctrl+R and specify the path

  ## Linux User Management
 • Person who uses the computer is called USER.
  ✓ On Linux their is tow kinds of users.
     ° # Root id = 0
     ° $ Normal user id = 1-999
•The root user have the power to do everything but if users want to
  have a root access they add "SUDO" in front of the command
    ✓ sudo- superuser do

   ## Creating Users
 • On Linux to creat users
     ✓ useradd - simple 
     ✓ adduser - ditailed
• the user files are stored inside /etc/passed.
• user password are stored inside /etc/shadow
  ° When you create a user it creates a group with the name
  #### To access root user
  #### sudo su
