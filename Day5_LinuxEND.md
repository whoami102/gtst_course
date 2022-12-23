        My name is abel,I take this note from learning geez tech security tester course.            
             Date 12/04/2015
  # 👩‍💻 Advanced Linux User.
## ✍️ On todays class
### Further on user management
### Linux file ownership +Permissions
### Software installation 
### Script installation
### Package installation common errors

 # Some advanced user commands
● To change password of user

○ sudo passwd username

● To change user id

○ sudo usermod -u new_id 
username

● To Delete User

○ sudo userdel -r username

● To Change users on terminal

# 🦸 Sudoers file
● The sudoers file is a file Linux and Unix administrators use to 
allocate system rights to system users

● The user you created doesn’t have power to use sudo as the 
original one. 

● This is Because it is not Added in the sudoers file 

● To access this file
#### sudo visudo
✓ You can add the User 
you need to have access 
 to the sudoers file, so he 
can use the sudo 
command.


  # Linux File permission
● Every file on linux have their own

○ Owner 

○ Permissions

● There is 5 main parts on the listing

○ Permission

○ Owners

○ Date

○ Size

○ filename

## Ownership
● Ownership is the owner of the file

● This have 2 kinds

○ User

○ Group

● To change the owner of file 
you can use the command 

○ chown user:group 
filename

## Permission

● There are 3 types of permissions

○ Read ( r )

○ Write ( w )

○ Execute ( x )

● The folders and files are differ with 
the ‘d’ and ‘-’
 on the beginning of 
the permission.

✓ There still the permission have three parts.
### user -group-other
● User ( u ) => power of user defined on the the 
ownership

● Group (g )=> power of group defined on the 
the ownership

● Other ( o ) => power of other users.

● All ( a ) => power of all which can be found in 
the 3 above owners 

● Command to change permission of file

○ chmod <option>filename

## CHMOD command

● This command helps to change file permission.

● Those file permissions are read,write & execute.

● Each of the permission have a number representations.

○ Read -> 4 - r

○ Write -> 2 - w

○ Execute -> 1 - x

● Syntax

○ chmod <parameter> filename

● The parameter can be in numbers and symbols

## A) Parameters in symbol
○ chmod a+x filename -> adding execute permission for all ( chmod +x filename)

○ chmod u+x filename -> adding execute permission for user

○ chmod g+x filename -> adding execute permission for group

○ chmod o+x filename -> adding execute permission for other

○ chmod -x filename -> removing execute permission for all

○ chmod a+rwx , u-rw , g-x , o-xw filename -> gives rwx for all and removes something from all
## B) Parameters in Number
● chmod 621 filename -> 6 for user, 2 for group, 1 for other ( 6 = 4+2 ), 6 =r w

● chmod 777 filename -> 7 for users, 7 for group , 7 for others (7 =4+2+1), 7 = rwx

## Package installation on linux

● ON linux to install softwares you use 
package managers.
○ Ex: apt,pacman,pkg,...
● We will use debian package manager.

● On debian the package manager i called 
‘APT’ also there is called ‘dpkg’

● Package managers are a free-software 
user interface that work with an online 
server to handle the installation and 
removal of software on Debian, and 
Debian-based Linux distributions.

## The repository

This is the site/ server kali use to 
upload the packages.

## Advanced package tool / apt /

● Apt is a free-software user interface that work with an 
online server to handle
 the installation and removal of 
software on Debian, and Debian-based Linux 
distributions.used for online and offline purpose.

● The old ‘apt’ used as ‘apt-get’

● Syntax

○ sudo apt updat
 
○ sudo apt search <softwarename>

○ sudo apt install <softwarename>

○ sudo apt remove <softwarename>

○ sudo apt upgrade 

○ sudo apt purge <softwarename> 

## Package dependencies 

● A software can be built based on another program 
called ‘modules’

● SO, a program to work properly, the dependencies have 
to be installed successfully. 

● Those package managers install the 
software+dependencies

## Dpkg / Debian package manager /

● Dpkg is an offline package managing 
program.

● Packages on debian have an extension 
“.deb”

● Syntax

○ sudo dpkg -i <packagename>

○ sudo dpkg -r <packagename>

○ sudo dpkg -P <packagename>

