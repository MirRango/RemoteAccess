# RemoteAccess

To shut dwon multipaly server via ssh:

first create a script fiel like:
1 sudo nanp poweroff.sh
2 Then write the below code onto your file:
#!/bin/bash
ssh -t x@x.x.x.x poweroff
ssh -t x@x.x.x.x poweroff
ssh -t x@x.x.x.x poweroff
ssh -t x@x.x.x.x poweroff
# -t option to allow for entering the sudo password when connected to the server.
Then save the file and give the file execute permission like: 
# sudo chmod +x pweroff.ssh
And when you want to run the scipt file:
# bash poweroff.ssh
