# EXP-02 Information Gathering

## AIM:

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
![image](https://github.com/Prasanna-936/InformationGathering/assets/130341982/f286464c-cfa5-4c44-aa97-d0bcfbd3a5b4)



## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

```
ping saveetha.ac.in
```
## Output:
![image](https://github.com/Prasanna-936/InformationGathering/assets/130341982/3157630d-5094-4d5f-9952-d8244ce19f77)




## Finding Hosting Company

get further detail by using ip2location.com website.


## Output:
![image](https://github.com/Prasanna-936/InformationGathering/assets/130341982/7ac9f166-a5f2-4c9c-ac04-60a2c362be44)




## History of the website:
https://web.archive.org/
## Output:
![image](https://github.com/Prasanna-936/InformationGathering/assets/130341982/908b9974-0db6-453d-8939-bf4b134007f5)


## Webserver Fingerprinting:
### Netcat:
```
ncat -C google.com
GET /HTTP/1.0
```

## Output:

![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/c80acbc3-a197-48b5-8ddc-d61d0d4e47b9)


## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
![image](https://github.com/Prasanna-936/InformationGathering/assets/130341982/644fe232-95c4-4422-9952-bc53d3a28770)




### Whatweb:
```
whatweb infosys.com
```
```
whatweb yahoo.com
```
```
whatweb -v -a 3 172.217.160.174
```
### Output:
![image](https://github.com/Prasanna-936/InformationGathering/assets/130341982/5bc767b4-79cc-4c5f-add0-360202c16645)




## httprint:
```
httprint -h 162.159.153.4 -s /usr/share/httprint/signatures.txt -P0 |more
```
### Output:

![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/6856bf1e-3c62-4cd2-8469-e7b523dada37)


## Tracing the Location
### TCP Traceroute:
```
sudo traceroute -T lms.ai.saveetha.in
```
## Output:
![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/d2a93aa7-3935-4174-a7f9-37bba41a7a0d)




## UDP Traceroute:
```
sudo traceroute -U lms.ai.saveetha.in
```
## Output:
![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/a91954da-205f-424e-ba97-ba83503d48f1)




## ICMP Traceroute:
```
sudo traceroute  lms.ai.saveetha.in
```
## Output:
![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/775a3e19-9691-44de-942f-1b293b237418)


## RESULT:
The information gathering techniques tools/procedure were identified successfully.
