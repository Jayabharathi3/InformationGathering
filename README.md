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


## OUTPUT:
```
 # ANALYSING WEBSITE : 
     FRESHWORKS.COM
 ```    
## WHOIS :

https://www.whois.com/whois/freshworks.com

![whois](https://github.com/Jayabharathi3/InformationGathering/assets/120367796/b3f44fc8-adab-4d16-8599-e2826dd71a22)


## IP2 LOCATION :

https://www.ip2location.com/demo/13.33.146.98

![ip2](https://github.com/Jayabharathi3/InformationGathering/assets/120367796/f0fd71bf-23bf-46a6-bd4a-2e9c213b8495)


## WEB ARCHIVE :

https://web.archive.org/details/freshworks.com

![webarchive](https://github.com/Jayabharathi3/InformationGathering/assets/120367796/e3ea2d4f-416b-40a8-8c92-06a007a5886a)


## NMAP :

nc 13.33.146.98
GET /

![nmap](https://github.com/Jayabharathi3/InformationGathering/assets/120367796/a690e369-4145-4588-9dd9-342de60cf1cf)


## WHATWEB :

whatweb freshworks.com

![whatweb1](https://github.com/Jayabharathi3/InformationGathering/assets/120367796/5be1040e-c94d-438f-8998-f83c65eb8124)

whatweb -v freshworks.com

![whatweb2](https://github.com/Jayabharathi3/InformationGathering/assets/120367796/df8fb68e-bea9-4605-aeba-5d37d8bf7248)

## HTTPRINT :

httprint -h 13.33.146.98 -s /usr/share/httprint/signatures.txt -P0 |more

![httprint](https://github.com/Jayabharathi3/InformationGathering/assets/120367796/58710a23-87df-4cbb-b343-312c3a07a4b7)


## TRACEOUT :

 ### TCP TRACEOUT :

 sudo traceroute -T www.freshworks.com

 ![tcp trace](https://github.com/Jayabharathi3/InformationGathering/assets/120367796/b3704e2c-a893-4bd8-8995-2eff8ff33c2f)


 ### UDP TRACEOUT :

sudo traceroute -U www.freshworks.com

 ![udp trace](https://github.com/Jayabharathi3/InformationGathering/assets/120367796/a31b12a1-d67c-4d0f-b166-2211faaa3fdb)


 ### ICMP TRACEOUT :

 sudo traceroute  www.freshworks.com

 ![icmp trace](https://github.com/Jayabharathi3/InformationGathering/assets/120367796/2d135fb8-5ac8-4ead-8d12-896e4944a327)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
