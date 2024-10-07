# InformationGathering
# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

# Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## output

![1 whois](2a.png)

# Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
## output

![2 ping](2b.png)

# Finding Hosting Company
get further detail by using ip2location.com website.
## output

![3 ip2location](2c.png)

# History of the website:
```
https://web.archive.org/
```
## output

![4 web archive](2d.png)

# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
## output

![5 nc command](2e.png)

## nmap:
## #output

![6 nmap](2f.png)

# Whatweb
## output

![7 whatweb](2g.png)

# httprint
## output

![8 httprint](2h.png)

# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output

![9 tcp traceroute](2i.png)

# UDP Traceroute:
sudo traceroute -U www.google.com
## output

![9 udp traceroute](2j.png)

# ICMP Traceroute:
sudo traceroute  www.google.com
## output

![9 ICMP traceroute](2k.png)

# Netcraft
## output

![10 netcraft](2l.png)

# Wapplyzer
## output

![11 wappalyzer](2m.png)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
