# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

Find out the ip address of the attackers system
## OUTPUT:
![ifconfig](https://github.com/Reebak04/Metasploit-for-reconnaissance/assets/118364993/1ee9b515-d992-48c2-8d68-ec66b61269f4)

## Invoke msfconsole
## OUTPUT:
![msfconsloe](https://github.com/Reebak04/Metasploit-for-reconnaissance/assets/118364993/3008e2ee-70c8-480c-b251-16d352a8f39b)

Type help or a question mark "?" to see the list of all available commands you can use inside msfconsole.
![help](https://github.com/Reebak04/Metasploit-for-reconnaissance/assets/118364993/3f316c4b-4cd4-418d-aa80-5a5f3180df68)

## Port scanning:
## msf > nmap -sT 192.168.1810/24-p1-1000
![image](https://github.com/Reebak04/Metasploit-for-reconnaissance/assets/118364993/88bb7f51-e65e-4076-ab34-b5fb4d2631cb)

## msf > db_nmap 192.168.181.0/24
![image](https://github.com/Reebak04/Metasploit-for-reconnaissance/assets/118364993/05ee469b-e4ac-49b5-baf9-df3266a08786)

## kali > ls-l
![ls](https://github.com/Reebak04/Metasploit-for-reconnaissance/assets/118364993/1c7803b4-0ed2-4e0e-a87e-a6d6685672d9)

## search 
![search](https://github.com/Reebak04/Metasploit-for-reconnaissance/assets/118364993/e8f48467-91a9-4b32-a5e3-825eebe8d473)

## info
![info](https://github.com/Reebak04/Metasploit-for-reconnaissance/assets/118364993/806242b3-0eff-4183-872c-a33b2fb0a6e2)
## MYSQL ENUMERATION
## db_nmap -sV -sC -p 3306 <metasploitable_ip_address>
![image](https://github.com/Reebak04/Metasploit-for-reconnaissance/assets/118364993/3561409d-97ef-4a9f-a47e-bd9d5be79903)
## search
![image](https://github.com/Reebak04/Metasploit-for-reconnaissance/assets/118364993/da995c5c-b4f5-4f61-b0f4-f0e03b3d3ebe)
##  use 11 Or: use auxiliary/scanner/mysql/mysql_version
![image](https://github.com/Reebak04/Metasploit-for-reconnaissance/assets/118364993/97a5eded-a893-4a00-bfb5-7c52369cecc3)
## Use the set rhosts command to set the parameter and run the module, as follows:
![image](https://github.com/Reebak04/Metasploit-for-reconnaissance/assets/118364993/6dbe03e3-405b-45e5-b86f-16afa5f7cf24)
## After scanning, you can also brute force MySQL root account via Metasploit's auxiliary(scanner/mysql/mysql_login) module.
![image](https://github.com/Reebak04/Metasploit-for-reconnaissance/assets/118364993/5ff81cd2-b37b-4a7e-86c9-4d2a31d262f4)
## /usr/share/wordlists: set PASS_FILE /usr/share/wordlistss/rockyou.txt 
![image](https://github.com/Reebak04/Metasploit-for-reconnaissance/assets/118364993/56d9ed2c-f63d-4c91-a504-d08debcace37)
![image](https://github.com/Reebak04/Metasploit-for-reconnaissance/assets/118364993/bfc568ac-c5c3-4dcf-a057-47f7bb03ecb1)

## RESULT:
The Metasploit framework for reconnaissance is  examined successfully
