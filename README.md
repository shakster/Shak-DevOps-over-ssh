This python3 network automation app attempts to ssh onto a pre-defined list of IP addresses. It requires the paramiko library installed

pip3 install paramiko

and not much else (that I can remember as I write this)

It requires the 3 files with the instructions:

user.txt - The username and password, comma separated (careful with your creds... chmod 700)
commands.txt - The commands to be executed on each device
ips.txt - The IP addresses that the commands will be executed on

Still to do:
- Figure out NEW line on ssh output - although the terminal exection shows "\r\n" it does not go to new line on my MAC :(# Shak-DevOps-over-ssh
