# Lab 02 - Linux Terminal Commands

This lab involves running a series of commands in a Linux terminal. For each command, a short description is provided along with a placeholder for the command's output.

## hostname

**Description:** Show or set the system host name.

**Command:** `hostname`

**Output:**
```
JoePC
```


## env

**Description:** Run a program in a modified environment or print current environment variables.

**Command:** `env`

**Output:**
```
ProgramFiles(x86)=C:\Program Files (x86)
!::=::\
CommonProgramFiles(x86)=C:\Program Files (x86)\Common Files
asl.log=Destination=file
SHELL=/usr/bin/bash
NUMBER_OF_PROCESSORS=16
FPS_BROWSER_USER_PROFILE_STRING=Default
PROCESSOR_LEVEL=6
TERM_PROGRAM_VERSION=3.6.3
JULES_LAUNCHER_PATH=C:\Program Files\JulesApp\JulesApp.exe
MINGW_PREFIX=/mingw64
ACSvcPort=17532
PKG_CONFIG_PATH=/mingw64/lib/pkgconfig:/mingw64/share/pkgconfig
USERDOMAIN_ROAMINGPROFILE=JOEPC
HOSTNAME=JoePC
PROGRAMFILES=C:\Program Files
MSYSTEM=MINGW64
PATHEXT=.COM;.EXE;.BAT;.CMD;.VBS;.VBE;.JS;.JSE;.WSF;.WSH;.MSC
ORIGINAL_TEMP=/c/Users/Joeyc/AppData/Local/Temp
MINGW_CHOST=x86_64-w64-mingw32
OS=Windows_NT
NVM_SYMLINK=C:\Program Files\nodejs
HOMEDRIVE=C:
MSYSTEM_CARCH=x86_64
USERDOMAIN=JOEPC
PWD=/home/Joeyc
USERPROFILE=C:\Users\Joeyc
OneDriveConsumer=C:\Users\Joeyc\OneDrive
MANPATH=/mingw64/local/man:/mingw64/share/man:/usr/local/man:/usr/share/man:/usr/man:/share/man
PRINTER=HP66F5CA (HP Color LaserJet Pro M478f-9f)
TZ=America/New_York
MINGW_PACKAGE_PREFIX=mingw-w64-x86_64
ALLUSERSPROFILE=C:\ProgramData
ORIGINAL_PATH=/c/Windows/System32:/c/Windows:/c/Windows/System32/Wbem:/c/Windows/System32/WindowsPowerShell/v1.0/
CommonProgramW6432=C:\Program Files\Common Files
HOME=/home/Joeyc
USERNAME=Joeyc
OneDrive=C:\Users\Joeyc\OneDrive
COMSPEC=C:\WINDOWS\system32\cmd.exe
APPDATA=C:\Users\Joeyc\AppData\Roaming
SYSTEMROOT=C:\WINDOWS
LOCALAPPDATA=C:\Users\Joeyc\AppData\Local
COMPUTERNAME=JOEPC
INFOPATH=/mingw64/local/info:/mingw64/share/info:/usr/local/info:/usr/share/info:/usr/info:/share/info
TERM=xterm
NVM_HOME=C:\Users\Joeyc\AppData\Roaming\nvm
LOGONSERVER=\\JOEPC
ACLOCAL_PATH=/mingw64/share/aclocal:/usr/share/aclocal
USER=Joeyc
PSModulePath=C:\Program Files\WindowsPowerShell\Modules;C:\WINDOWS\system32\WindowsPowerShell\v1.0\Modules
RlsSvcPort=22112
BESIEGE_UNITY_ASSEMBLIES=C:/Program Files/WindowsApps/SpiderlingStudios.5821136CAA5A2_1.0.18.0_x64__a408ere9ra7h8/Besiege_Data\Managed/
TEMP=/tmp
MSYSTEM_CHOST=x86_64-w64-mingw32
ORIGINAL_TMP=/c/Users/Joeyc/AppData/Local/Temp
SHLVL=1
PROCESSOR_REVISION=9e0d
DriverData=C:\Windows\System32\Drivers\DriverData
COMMONPROGRAMFILES=C:\Program Files\Common Files
LC_CTYPE=en_US.UTF-8
PROCESSOR_IDENTIFIER=Intel64 Family 6 Model 158 Stepping 13, GenuineIntel
SESSIONNAME=Console
PS1=\[\e]0;\w\a\]\n\[\e[32m\]\u@\h \[\e[35m\]$MSYSTEM\[\e[0m\] \[\e[33m\]\w\[\e[0m\]\n\$
PKG_CONFIG_SYSTEM_LIBRARY_PATH=/mingw64/lib
HOMEPATH=\Users\Joeyc
XDG_DATA_DIRS=/mingw64/share/:/usr/local/share/:/usr/share/
MSYSCON=mintty.exe
TMP=/tmp
CONFIG_SITE=/etc/config.site
PATH=/mingw64/bin:/usr/local/bin:/usr/bin:/bin:/c/Windows/System32:/c/Windows:/c/Windows/System32/Wbem:/c/Windows/System32/WindowsPowerShell/v1.0/:/usr/bin/site_perl:/usr/bin/vendor_perl:/usr/bin/core_perl
ProgramW6432=C:\Program Files
BESIEGE_GAME_ASSEMBLIES=C:/Program Files/WindowsApps/SpiderlingStudios.5821136CAA5A2_1.0.18.0_x64__a408ere9ra7h8/Besiege_Data\Managed/
MSYSTEM_PREFIX=/mingw64
WINDIR=C:\WINDOWS
FPS_BROWSER_APP_PROFILE_STRING=Internet Explorer
PROCESSOR_ARCHITECTURE=AMD64
PUBLIC=C:\Users\Public
PKG_CONFIG_SYSTEM_INCLUDE_PATH=/mingw64/include
SYSTEMDRIVE=C:
OLDPWD=/
TERM_PROGRAM=mintty
ProgramData=C:\ProgramData
_=/usr/bin/env
```


## ps

**Description:** Report a snapshot of the current processes.

**Commandd:** 'ps'

**Output:**
```
PID    PPID    PGID     WINPID   TTY         UID    STIME COMMAND
     1257       1    1257      17744  ?         197609 17:55:52 /usr/bin/mintty
     1282    1258    1282      25036  pty0      197609 18:25:09 /usr/bin/ps
     1258    1257    1258       5696  pty0      197609 17:55:52 /usr/bin/bash
```


## pwd

**Description:** Outputs the current working directory.

**Commandd:** 'pwd'

**Output:**
```
/home/Joeyc
```


## git clone <remote_repo_url>

**Description:** Clones a remote git repository.

**Commandd:** 'git clone <remote_repo_url>'

**Output:**



## cd <folder>

**Description:** Changes the current working directory.

**Commandd:** 'cd <folder>'

**Output:** 



## ls

**Description:** Lists the contents of the current working directory.

**Commandd:** 'ls'

**Output:**



## df

**Description:** Report file system disk space usage.

**Commandd:** 'df'

**Output:**



## mkdir <folder>

**Description:** Makes an empty folder at the specified path.

**Commandd:** 'mkdir <folder>'

**Output:**



## nano <file>

**Description:** Opens the nano text editor for the specified file.

**Commandd:** 'nano <file>'

**Output:**



## cat <files...>

**Description:** Concatenates files and prints them to standard output.

**Commandd:** 'cat <files...>'

**Output:**



## cp <file1> <file2>

**Description:** Copies files from one location to another.

**Commandd:** 'cp <file1> <file2>'

**Output:**



## mv <file1> <file2>

**Description:** Moves files from one location to another.

**Commandd:** 'mv <file1> <file2>'

**Output:**



## rm <files...>

**Description:** Removes files or directories.

**Commandd:** 'rm <files...>'

**Output:**



## clear

**Description:** Clears the terminal's screen.

**Commandd:** 'clear'

**Output:**



## man

**Description:** 'Opens the system manual for the specified program.'

**Commandd:** 'man <command>'

**Output:**



## uname

**Description:**  Prints system information.

**Commandd:** 'uname'

**Output:**



## ifconfig

**Description:** Configures or displays network interface parameters.

**Commandd:** 'ifconfig'

**Output:**



## ping <ip>

**Description:** Sends ICMP ECHO_REQUEST packets to network hosts.

**Commandd:** 'ping <ip>'

**Output:**



## netstat

**Description:** Prints network connections, routing tables, and other network interface statistics.

**Commandd:** netstat

**Output:**
