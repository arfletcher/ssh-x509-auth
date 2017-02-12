# ssh-x509-auth
X509 authentication plugin for SSH daemon

SSH AuthorizedKeysCommand Script
--------------------------------
This set of scripts enables the SSHD daemon to retrieve smart card X509
certificates from a central register.

Configuration Files
-------------------
There is a default configuration which can be overridden in the file 
/etc/ssh-x509-auth.conf (packaged) or /etc/ssh-x509-auth.d/*.conf for
local changes as appropriate.
