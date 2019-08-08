### TMUX [Terminal Multiplexer]
* [CheatSheet](https://danielmiessler.com/study/tmux/)
* Basic Commands
  1. create new session  
  tmux new -s kkpalwiki
  2. Run program  
  htop
  3. Detach session  
  Ctrl-B + D -----------Detach the sessions
  4. check for any tmux session running  
  tmux list-sessions
  5. Attach a running session  
  tmux a -t kkpalwiki



* Kernel version 
  * uname -a
* Disk capacity
  * df -ah
* Manage service
  * service <servicename> status (old)
  * systemctl status <servicename>
* Size of folder
  * du -sh <folder>
* Check open ports, network services
  * netstat
* CPU usage of process
  * ps -aux | grep <processname>

* Syntax highlighting of Vim editor
  * syntax enable in ~/.vimrc



### Compress Decompress
* ZIP
    * Directory = zip -r archive.zip dir_to_zip
* UNZIP
    * unzip x.zip -d /path/to/new/dir
* TAR
  * tar -zcvf archive_name.tar </path/to/directory_to_compress>
  * tar -zxvf archive_name.tar


### Vim commands for MAC
* Pageup/PageDown - Shit + fn + up/down key
* First line in file - gg
* Last line in file - G
* Start of line - 0
* Undo last changes - u
* tabspace change - set ts=4

### Distinct
cat train.jsonl | sort | uniq > trainUnique.jsonl
