# Subdomain-Enumeration
This is a python script used for subdomain enumeration
The script will use a list of potential subdomains and prepends them to the domain name provided via a command-line argument.
The script then tries to connect to the subdomains and assumes the ones that accept the connection exist.

#Explanation
The script will search for subdomains.txt. This list should be in the same directory as the python script

#Running the script
SE.py <domain>
