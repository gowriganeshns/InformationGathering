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

## whois 

![image](https://github.com/gowriganeshns/InformationGathering/assets/118120621/9ce7be0f-737a-4549-a873-1dd3db127616)

## ip2location

![image](https://github.com/gowriganeshns/InformationGathering/assets/118120621/2cb562f6-3b42-4528-8daf-dfc7466583b5)

## web archive

![image](https://github.com/gowriganeshns/InformationGathering/assets/118120621/b02f432b-d103-4594-981a-5e94e1fbb109)

## webserver Fingerprinting:

## netcat:
```
nc 172.17.52.118 80
```
## Output

![image](https://github.com/gowriganeshns/InformationGathering/assets/118120621/c4047c64-2a1c-44bd-bede-f1914ab6c5b7)

## Nmap:

```
nmap -p 21 -sV --script=banner ftp.vim.org
```
# output

![image](https://github.com/gowriganeshns/InformationGathering/assets/118120621/545b8911-27a8-4e20-bbe4-b6666f21fedd)

## whatweb:
```
whatweb infosys.com

```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```

## output

![image](https://github.com/gowriganeshns/InformationGathering/assets/118120621/215996ce-ec8b-4618-b508-f1846d37263a)
![image](https://github.com/gowriganeshns/InformationGathering/assets/118120621/078e929e-dfc7-4bca-a765-d14ea1ded66e)

## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## output

![image](https://github.com/gowriganeshns/InformationGathering/assets/118120621/24db16da-8044-4a6a-974c-6fca2a5ad69d)

## Tracing the Location:

## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in

```

## output

![image](https://github.com/gowriganeshns/InformationGathering/assets/118120621/7713042b-a007-4144-bb4a-b90a6e230e35)

## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in

```
## output
![image](https://github.com/gowriganeshns/InformationGathering/assets/118120621/968d7d00-5303-4e7e-82a4-acf80e438c39)

## ICMP Ttaceroute:
```
sudo traceroute  www.saveetha.ac.in
```
![image](https://github.com/gowriganeshns/InformationGathering/assets/118120621/3cefbc79-5cf6-43d3-a1bd-0bc9ec9bdd6e)
















## RESULT:
The information gathering techniques tools/procedure were  identified successfully
