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
Tested by :RAHUL RP
Register number:212224240125

## OUTPUT:

![image](https://github.com/user-attachments/assets/e4be2f55-2234-44eb-9afd-033129e10b60)

## Finding IP address:
## ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
## ping saveetha.ac.in

## output:

![image](https://github.com/user-attachments/assets/6b143703-8330-4edd-85be-552e04d17891)

## Finding Hosting Company:

## get further detail by using ip2location.com website.

## output:

![image](https://github.com/user-attachments/assets/71f403c4-0d5d-4eaf-b821-970b20d6642c)

## History of the website:

## Output:

![image](https://github.com/user-attachments/assets/8eabb6b1-39e7-49b1-8f3d-41716afeb5da)

## Webserver Fingerprinting:

## Netcat: nc 172.17.52.118 80
## OUTPUT:

![image](https://github.com/user-attachments/assets/4a96e747-811d-4cd7-b185-1bb44e04c10e)

## nmap:
## nmap -p 21 -sV --script=banner ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/efd09eec-a07b-4519-8ae4-57e5c9a0ee7c)

## Whatweb:
## whatweb infosys.com
## whatweb zoho.com
## whatweb -v -a 3 172.17.52.201
## OUTPUT:
![image](https://github.com/user-attachments/assets/a8b94f3f-6fe0-44c2-85d2-1ecb941fa45a)


## httprint:
## httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
## OUTPUT:

![image](https://github.com/user-attachments/assets/c20d6d9f-a409-46c0-9853-91900b2e1cc0)

## Tracing the Location
## TCP Traceroute:
## sudo traceroute -T www.saveetha.ac.in
## OUTPUT:

![image](https://github.com/user-attachments/assets/789e61cf-c373-487a-b467-b45ebe91cf18)

## UDP Traceroute:
## sudo traceroute -U www.saveetha.ac.in
## OUTPUT:
![image](https://github.com/user-attachments/assets/0dbcabde-6aa5-4991-a768-f87acaab52ff)

## ICMP Traceroute:
## sudo traceroute www.saveetha.ac.in
## OUTPUT:

![image](https://github.com/user-attachments/assets/99cf011b-eb95-4020-ba6d-d1b7d84dbeed)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
