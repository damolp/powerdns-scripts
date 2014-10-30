#powerdns-scripts
================
#Random PowerDNS stuff


## Pipe Backend Files:
	[malware.py](malware.py) - uses justdomains file from malwaredomains.com to generate a sinkhole
	

### Usage in pdns.conf or pdns.d/*:
	`
	#you can run multiple pipe backends together
	#see http://doc.powerdns.com/html/modules.html 
	launch=pipe
	pipe-command=/path/to/pipe/script
	pipe-timeout=500
	`