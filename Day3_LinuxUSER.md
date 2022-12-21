      # Day3_linuxUSER.md
    ## Overview of kali Linux
   ### 1 Information gathering
- Tools for information gathering in system network host.
   _ Dimitry
   _ ike-scan
   _ legion
   _ maltego ... 
 
   ### 2 Vulnerability Analysis
- for finding Vulnerabilities. 
   _ legion.     _ nmap
   _ lynis       _ Unix prives
   _ nikto

   ### 3 Web Application Analysis
_ for finding Vulnerabilities and exploits on websites.
   _ burpsuite.    _ skipfish
   _ Commix.       _ sqlmap
   _ httrack.      _ webscarab
   _ paros.        _ wpscan
  
   ### 4 Database Assessment
- tools for finding Vulnerabilities and exploits on database.
   _ jsql inject
   _ mdb-sql
   _ oscanner
   _ sidguesser...
 
   ### 5 Password Attacks
- tool for exploiting passwords for login websites, application, Windows.
   _ cewl
   _ crunch
   _ hashcat
   _ johnny...
   ### 6 Wireless Attacks 
- for exploiting wireless systems like wifi, Bluetooth.
    _ aircrack-ng
    _ chirp
    _ cowpatty
    _ kismet...

   ### 7 Reverse Engineering
- for exploiting softwares,mobile applications and any binary files.
     _ apktool
     _ clang
     _ ghidra
     _ javasnoop
   
   ### 8 Exploitation Tools
- tools for exploiting softwares mobile computers websites and any things.
     _ armitage
     _ metasploit
     _ social engineering
     _ termineter
 
    ### 9 Sniffing and Spoofing
- tools for listening or hijacking networks.
     _ driftnet
     _ hamster
     _ responder
     _ Wireshark
  
    ### 10 Post Exploitation
- for maintaining our access.used after exploiting a system.
     _ backdoor-f
     _ weevely
     _ exe2hex
     _ nishang
     _ proxychains4
  
    ### 11 Forensics
- tools for doing researches and investigate a cyber attacks.
      _ autopsy
      _ binwalk
      _ foremost
      _ galleta
      _ hashdeep

    ### 12 Reporting tools
- tools for report preparation.after some forensic you will get data and you will write
    report and these tools will help you.
   _ cutycapt.        _ maltego
   _ dradis frame.    _ pipal
   _ faraday IDE.     _ recordmyd
 
    ### 13 Social Engineering Tools
- used for social engineering attacks.
    _ back door      _ MSF payload
    _ beef xss fra     _ social engineering 
    _ maltego
  
     ### 14 System Services
- Buttons used to start some services
    _ beef starts
    _ beef stop
    _ dradis start
    _ dradis stop

      ### 15 Usually used applications
- softwares for some basic purposes 


       ## Folder Managers 
 1, Dolphin
 2, Thunar
 3, Nautilus
   - on windows it's not free

    ## Linux Commands
 - Linux system uses shall(terminal).the shall help us to communicate with the
   kernel and help to execute code.
   
    ### Linux command basics
- command is a small programs that do one task well.

   #### _ LS/ list directory
List information about the files
   _ ls-l
   _ ls-a
   _ LS filename 

   ####  _ CD/ change Directory
- it is used to change current working directory.
   _ CD/-root
   _ CD  home
   _ CD.. 1x back
   _ CD../.. 2x back 
   _ CD filename
 
   #### _ pwd/ print working directory
- it prints the path of the working directory.
    starting from root.

   #### _ echo
- Is used to display line of text/starting that are passed as an argument this
   is mostly used in shell scrips and batch files to output status text to the 
    screen or a file.
       _ echo text > file.txt
       _ echo text >> file.txt

   ####  Cat/ head/ tail/ less
- used to show the content of a file
      _ cat file

   #### touch
- creat any kind of file with the name you gave it with empty inside
      _ touch (file)

    ####  mkdir/ make directory
- creat folder with the name you gave it
     _ mkdir"folder name"


    #### rm / remove
- remove file
       _ rm-r(4 folders)
       _ rm-rf 

    #### CP/MV / copy, move
   _ CP/mv file and folder

   #### grep/ global search for regular expression
- the grep filter searches a file for a particular pattern of characters and
     displays all lines that is contain that pattern.
      _ grep-i" search" file
         Case insensitive
     _ grip-l" search" file
          displays filename
     _ grip-r
          Search text in folders

    #### Wc/ word count
- it is used to find out number of lines word count in the file spacified in 
    the file arguments. 
  Line(-l). Word (-w).  Batter (-c)

   ## Multiple command executions
   
       #### And(&&)
- commands you entered will be executed.if both are working without error.

     #### OR (||)
- the command will be expected.if it have error or not

     #### pipeing (|)
- will help you run commands by using the out put of the 1st command as the 
    input for the next one.
Continued...

   
        
