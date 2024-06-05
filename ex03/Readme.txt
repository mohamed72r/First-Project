An SSH key is an access identifier for the SSH (Secure Shell) network protocol
Use the following procedure to generate an SSH key pair on UNIX and UNIX-like systems:
1.Run the ssh-keygen command.
You can use the "-t" option to specify the type of key to create.
"ssh-keygen -t rsa"
The command prompts you to enter the path to the file in which you want to save the key.
2.A default path and file name are suggested in parentheses.
 For example: /home/user_name/.ssh/id_rsa. To accept the default path and file name, press Enter.
Otherwise, enter the required path and file name, and then press Enter.
3.The command prompts you to enter a passphrase.
The passphrase is not mandatory if you want to log in to an instance created using an Oracle-provided image.
However, it is recommended that you specify a passphrase to protect your private key against unauthorized use.
