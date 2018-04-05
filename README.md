# XRDP_debian_9_LXDE

On base Debian 9 installed GUI LXDE-core, configure and installed XRDP and XORGRDP for connected to server by RDP.
Is created one user and set password which genereted with utilites mkpasswd --method=sha-512.
In LXDE installed browsers Firefox and Google-Chrome, mail client Thunderbird.
Turned off  xscreensaver and poweroff.

To start you need change in inventory file (hosts) ip in ansible_host.
In playbook (xrdp.yml) change name user (USER_NAME) which need to created and change password (USER_PASSWORD) with generated mkpasswd --method=sha-512.
