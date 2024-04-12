# To perform information gathering techniques

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
![image](https://github.com/gowriganeshns/InformationGathering/assets/130341982/192c7676-5879-407c-bda5-bcc565a5f30d)




## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

```
ping saveetha.ac.in
```

## Output:
![image](https://github.com/gowriganeshns/InformationGathering/assets/130341982/7ceb7d38-ae3e-46e6-a956-ff72a3ad0acc)



## Finding Hosting Company

get further detail by using ip2location.com website.


## Output:
![image](https://github.com/gowriganeshns/InformationGathering/assets/130341982/04824182-9190-4e57-a393-8a28f07d4a33)




## History of the website:
https://web.archive.org/
## Output:
![image](https://github.com/gowriganeshns/InformationGathering/assets/130341982/8a25b6bd-72e4-457b-990a-4da2afac8546)



## Webserver Fingerprinting:
### Netcat:
```
ncat -C google.com
GET /HTTP/1.0
```

## Output:

![image](https://github.com/gowriganeshns/InformationGathering/assets/130341982/d10e0f66-8036-4181-98c7-5f58da50c94c)



## nmap:
```
nmap -vvv -sV 192.168.23.133
```
## Output:
![image](https://github.com/gowriganeshns/InformationGathering/assets/130341982/9305bac5-288c-47da-9a6e-52f5c0e3c513)




### Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
### Output:
![image](https://github.com/gowriganeshns/InformationGathering/assets/130341982/440b2cf8-9ebc-48c8-b90c-a9b850405997)




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
