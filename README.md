# InformationGathering
Information Gathering Techiques

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

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output
<img width="1600" height="537" alt="4" src="https://github.com/user-attachments/assets/203ca85a-614f-4a45-bec6-017f987bff87" />

## Finding Hosting Company
get further detail by using ip2location.com website.
##output
<img width="825" height="771" alt="image" src="https://github.com/user-attachments/assets/d9ac1517-acf2-4537-8b6d-8718dc0cbaba" />



## History of the website:
## output
<img width="692" height="731" alt="image" src="https://github.com/user-attachments/assets/e620a9e8-30ae-4e71-a772-5dd72d29ca47" />

# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
<img width="1600" height="306" alt="10" src="https://github.com/user-attachments/assets/a596d300-bf0b-455f-adbe-472e44a29d00" />

## nmap:
###output
<img width="1600" height="354" alt="5" src="https://github.com/user-attachments/assets/717366b2-66d6-4429-b45e-6e31fce4eeec" />


## Whatweb
### output
<img width="1600" height="306" alt="10" src="https://github.com/user-attachments/assets/8f0a367f-1d0b-40fe-b137-63a19ee3aa27" />


## httprint
### output
<img width="1543" height="647" alt="6" src="https://github.com/user-attachments/assets/26abaa86-aa26-4236-bcb4-2885ce4cc5b3" />

# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output
<img width="1600" height="272" alt="7" src="https://github.com/user-attachments/assets/384a0c1b-40af-4bec-8895-83d13cd3c3f9" />


## UDP Traceroute:
sudo traceroute -U www.google.com
## output
<img width="1317" height="657" alt="8" src="https://github.com/user-attachments/assets/43068d16-f704-408a-aeba-5deea962f46c" />

## ICMP Traceroute:
sudo traceroute  www.google.com
## output
<img width="957" height="157" alt="9" src="https://github.com/user-attachments/assets/8642d299-8efe-437b-a33b-e44990da013f" />

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
