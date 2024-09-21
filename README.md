# OFFSEC-OSCP Notes


Whois
```powershell
whois megacorpone.com -h 92.168.1.10   #check admin name for username, tech name for position, name server for the domain
whois 38.100.193.170 -h 192.168.50.251   #reverse lookup. u can check who is hosting the IP address from Organization
```

Google Hacking
```powershell
site:  #limit results from certin domain
filetype:  #limit search results to the specified file type
ext:PHP  #programming language might be used on a website
-filetype:HTML  #exclude particulor item from the results
intitle:"indexof" "parent directory"  #find pages that contain "index of" in the title and the words "parent directory" on the page
https://www.exploit-db.com/google-hacking-database
```

Netcraft
```powershell
#tech that r running on a specific website
#use 'https://searchdns.netcraft.com' to gather info about particular domain
```

Open-Source Code
```powershell
#you maybe able to gather sensitive data from publicly uploaded source code
#use 'Gitrob' & 'Gitleaks' to automate the process
./gitleaks-linux-amd64 -v -r=https://github.com/abdullahzuhair21/
```

Shodan
```powershell
#Google and other search engines search for web server content, while Shodan searches for internet-connected devices, interacts with them, and displays information about them.
hostname:megacorpone.com
```

SSL & TLS
```powershell
#use https://securtiyheaders.com to analyze HTTP response
#use https://www.ssllabs.com/ssltest analyze server's SSL/TLS configuration and compares it against current best practices (identify vuln like Poodle or Heartbleed)
```
