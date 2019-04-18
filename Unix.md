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
