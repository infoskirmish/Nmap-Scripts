# Nmap

Use
1. Copy the script file you want to your nmap script folder.
example (Ubuntu /usr/share/nmap/scripts/)

2. Use script in scan
example: nmap --script ftp-anon-better -n -p 21 -Pn -sT -T3 -O -D RND -oN scan.txt --randomize-hosts --spoof-mac cisco 127.0.0.1
