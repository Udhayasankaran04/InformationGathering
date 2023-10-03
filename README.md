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
Following Categories of pen test tools are identified for information gathering: Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network. http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc

## OUTPUT:
![image](https://github.com/Udhayasankaran04/InformationGathering/assets/119393933/11a2f114-74bf-4221-85e7-b4a2cdc21993)
## FINDING IP ADDRESS:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## OUTPUT:
![image](https://github.com/Udhayasankaran04/InformationGathering/assets/119393933/94ca4861-e642-4c09-ab9a-8a0eafa79c0b)
## FINDING HOSTING COMPANY
get further detail by using ip2location.com website.
## OUTPUT:
![image](https://github.com/Udhayasankaran04/InformationGathering/assets/119393933/8fc8d8f5-02af-4369-b68e-4e859d0e6fe4)
## HISTORY OF THE WEBSITE:

## OUTPUT:
https://web.archive.org/
![image](https://github.com/Udhayasankaran04/InformationGathering/assets/119393933/dfd905c6-05ae-42cc-87c9-322775aab10a)
```
nc 172.17.52.118 80
```
![image](https://github.com/Udhayasankaran04/InformationGathering/assets/119393933/35e265b1-f75c-4815-96c7-782b91e19c43)

## NMAP:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## OUTPUT:
![image](https://github.com/Udhayasankaran04/InformationGathering/assets/119393933/285f95e7-8451-403b-b36a-e02bcf2e9b47)

## WHATWEB:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
## OUTPUT:
![image](https://github.com/Udhayasankaran04/InformationGathering/assets/119393933/214dfa23-a2ae-462a-82f2-9a5ddeaabd36)

## HTTPRINT:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## OUTPUT:
![image](https://github.com/Udhayasankaran04/InformationGathering/assets/119393933/75719e40-c430-4665-b5f0-35c5716fa5bb)

## TRACING THE LOCATION

## TCP TRACEROUTE:
```
sudo traceroute -T www.saveetha.ac.in
```
## OUTPUT:
![image](https://github.com/Udhayasankaran04/InformationGathering/assets/119393933/20eb9735-08a4-4fb7-8fd1-cf15b25c833d)

## UDP TRACEROUTE:
```
sudo traceroute -U www.saveetha.ac.in
```
## OUTPUT:
![image](https://github.com/Udhayasankaran04/InformationGathering/assets/119393933/f19543d1-50c4-4219-9f43-24349e1018d4)

## ICMP TRACEROUTE:
```
sudo traceroute  www.saveetha.ac.in
```
## OUTPUT:
![image](https://github.com/Udhayasankaran04/InformationGathering/assets/119393933/17bee85c-919a-4f4e-8a27-9688a2daeb1c)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
