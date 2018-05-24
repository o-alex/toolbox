### Remote editing of files
1. Server - install rsub
```
wget -O /usr/local/bin/rsub \https://raw.github.com/aurora/rmate/master/rmate
chmod a+x /usr/local/bin/rsub
```
2. Local - install sublime 3
3. Local - sublime - install rsub
On Sublime Text 3, open Package Manager (Ctrl-Shift-P on Linux/Win, Cmd-Shift-P on Mac, Install Package), and search for rsub and install it
4. Local - run 
```
ssh -R 52698:localhost:52698 server_user@server_address
```
5. Server - run
rsub path_to_file/file.txt
