# Useful Linux commands

- Redo last command as root  
`sudo !!`

- Open an editor to run a command/s  
`ctrl + x + e`

- Run command, but don't put it into command history. (note the leading space)  
` ls -l`

- Fix a really long command that you messed up  
`fc`

- Tunnel with ssh (local port 3337 -> remote host's 127.0.0.1 on port 6379)  
`ssh -L 3337:127.0.0.1:6379 root@nuig.ie -N`

- Create a multiple folders  
`mkdir -p folder/{sub1,sub2}/{sub1,sub2,sub3}`

- Exit terminal but leave all processes running  
`disown -a && exit`