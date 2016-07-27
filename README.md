#This little script will help you to secure your OpenSSH-Server!
## What does it do?

	1. Check for root privileges
	2. Check if sshd_config exists
	3. Backup current 'sshd_config'
	4. Check OpenSSH-Server Version
	5. Change values in 'sshd_config':
		- Ciphers (will be added if not existing)
		- KexAlgorithms (will be added if not existing)
		- MACS (will be added if not existing)
		- Security Parameters
	6. Check if any errors occured
		- Output errors
		- Correction by user	
##TO-DO's: 
	- add OS detection
	- option to secure OpenSSH-Client
  

