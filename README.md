# burp_pro_install

#Description
This script install Burp Suite Pro v1.7.37
Activate Burp Suite Pro with Key-Generator and Key-Loader
Installtion
 burp_pro_installtion.mp4 
Launch Command (Powershell) :

irm burp.bughub.live | iex
Or

iwr -useb https://padsalatushal.github.io/burp_setup.ps1 | iex
If you are having TLS 1.2 Issues or You cannot find or resolve host then run with the following command:

[Net.ServicePointManager]::SecurityProtocol=[Net.SecurityProtocolType]::Tls12;iex(New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/padsalatushal/Burp-Suite-Pro-Installer/main/burp_setup.ps1')
If you are still having issues try changing your DNS provider to 1.1.1.1 or 8.8.8.8

Issues
If you encounter any challenges or problems with the script, I kindly request that you submit them via the "Issues" tab on the GitHub repository.

Support
This project needs a ⭐️ from you. Don't forget to leave a star ⭐️.
