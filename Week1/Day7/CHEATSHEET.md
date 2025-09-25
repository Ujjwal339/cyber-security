Filesystem & editing:-

ls -la
cd /path/to/dir
pwd
cat file.txt
less file.txt
nano file.txt

Permissions & processes:-

chmod 644 file.txt
chmod +x script.sh
chown user:group file.txt
ps aux | grep process
top
kill <pid>


Networking:- 
ip a
ping -c 4 8.8.8.8
ss -tuln
netstat -antp
traceroute google.com
nslookup google.com
dig google.com


Nmap & Wireshark basics:-

nmap -sn 192.168.1.0/24
nmap -sV -O 192.168.1.101
wireshark # GUI
# Useful Wireshark filters
http
dns
ip.addr == 192.168.1.101
tcp.port == 80
