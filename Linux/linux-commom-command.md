### See which ports are open
netstat -ntlp | grep LISTEN

### kill a process on a port on ubuntu
sudo kill \`sudo lsof -t -i:9001\`

or

sudo kill $(sudo lsof -t -i:9001)
