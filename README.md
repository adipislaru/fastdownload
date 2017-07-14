# FastDownload

This is a simple snippet of installing fast download for sv_downloadurl of HL1 Engine Games into GameCP and Nginx Web Server.
Used this in the past and hope it will be usefull for someone else.

# Info
  - **fast_download.conf** is the **nginx** configuration file
  - **gamecp_install.txt** and **gamecp_uninstall.txt** are the scripts for instal/uninstall that you should use with **GameCp**
  - In the **nginx** configuration file, */var/www/webservers/fast.yourdomain.ro/* is the location where the *sv_downloadsurls* should be.
  - As you can see in the install script, the link to the dldurl will be like this: ***yourdomain.tld:PORT/SERVER_IP-SERVER_PORT-SERVICE_ID/***
