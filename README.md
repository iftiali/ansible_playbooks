# ansible_playbooks
#All playbooks are tested and run on Ubuntu and CentOS systems

#This is the default ansible 'hosts' file.

#It should live in /etc/ansible/hosts
#- Comments begin with the '#' character
#- Blank lines are ignored
#- Groups of hosts are delimited by [header] elements
#- You can enter hostnames or ip addresses
#- A hostname/ip can be a member of multiple groups

# Ex 1: Ungrouped hosts, specify before any group headers.



# Ex 2: A collection of hosts belonging to the 'webservers' group
[control]
127.0.0.1


[webservers]
#hyderabad
#karachi
192.168.0.20
#192.168.0.105


# If you have multiple hosts following a pattern you can specify
# them like this:

## www[001:006].example.com

# Ex 3: A collection of database servers in the 'dbservers' group

[lb]
192.168.0.21

#y
#q
##
 #db01.intranet.mydomain.net
 #db02.intranet.mydomain.net
 #10.25.1.56
 #10.25.1.57

# Here's another example of host ranges, this time there are no
# leading 0s:

## db-[99:101]-node.example.com


