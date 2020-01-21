OPENVPN with system user access

Add server-tcp.conf file to /etc/openvpn/ directory
Download clientWin.ovpn file to windows machine
Download OpenVPN client for Windows
Run OpenVPN on the server via the following command 
systemctl restart openvpn@server-tcp
Add to autostart
systemctl enable openvpn@server-tcp
