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
