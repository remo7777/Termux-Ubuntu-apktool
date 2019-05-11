
# Termux-ubuntu-apkool #

android app payload embeding tool for termux

## Requirement

1. metasploit-framwwork 
(on termux)

2. bash shell 
( my tool is based on bash shell .. if you want to know which shell you are using on termux then type command `echo $SHELL` or `echo $0`) 

## Installation:..

 `git clone https://github.com/remo7777/Termux-ubuntu-apkool.git` 

 `cd Termux-ubuntu-apktool` 

 `bash setup` (no need any execute permission )

open new session...

 `bash ubuntu.sh` 

after installation complete... Goto old session

 `bash setup ubuntu` 

then again goto old session and type

 `bash ~/start-ubuntu.sh` ( it ll login to ubuntu environment)

then type 

`ls` 

next

 `bash setup` 

## Now tool is ready to use

Both terminal has same command ( termux and unubtu) which is `bind-apk` 

to know about how to use that bind-apk on both environment check on YouTube

type command on termux it ll redirect on YouTube

 👇 

 `echo "YW0gc3RhcnQgLWEgYW5kcm9pZC5pbnRlbnQuYWN0aW9uLlZJRVcgLWQgaHR0cHM6Ly95b3V0dS5i ZS9Bc0kxZzhfY21Idwo=" | base64 -d | bash` 

or

 `am start -a android.intent.action.VIEW -d https://youtu.be/AsI1g8_cmHw` 

#end#...
