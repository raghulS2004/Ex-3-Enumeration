# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
## OUTPUT
1<img width="446" alt="image" src="https://github.com/AsinVardhini/Enumeration/assets/119417735/aa6aa165-987d-4081-8001-3fe4f3ca9585">


filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

## OUTPUT
<img width="412" alt="image" src="https://github.com/AsinVardhini/Enumeration/assets/119417735/bc2355a5-d16b-4d31-98e0-280dea61785e">

intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
## OUTPUT
<img width="420" alt="image" src="https://github.com/AsinVardhini/Enumeration/assets/119417735/3559ae62-6d8f-4b38-95ef-2582e990e22c">

inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
## OUTPUT
<img width="426" alt="image" src="https://github.com/AsinVardhini/Enumeration/assets/119417735/6c358b29-fd42-45c4-91d4-2c7f46015070">


intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
## OUTPUT
<img width="425" alt="image" src="https://github.com/AsinVardhini/Enumeration/assets/119417735/3d281a98-9b23-405b-b1c6-571938c37328">

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
## OUTPUT
<img width="419" alt="image" src="https://github.com/AsinVardhini/Enumeration/assets/119417735/0a248995-64c1-415d-844a-b70ed3d36758">

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
## OUTPUT
<img width="416" alt="image" src="https://github.com/AsinVardhini/Enumeration/assets/119417735/2291833a-7427-4f65-afcc-b03293b8ebf5">

 
#DNS Enumeration


##DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:
<img width="363" alt="image" src="https://github.com/AsinVardhini/Enumeration/assets/119417735/7038f1fd-9fee-45d4-80a2-2331fbde161b">



<img width="418" alt="image" src="https://github.com/AsinVardhini/Enumeration/assets/119417735/d408fb61-d3fe-4a62-b4e1-31866a61eb25">





##dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.
## OUTPUT:
<img width="373" alt="image" src="https://github.com/AsinVardhini/Enumeration/assets/119417735/ab849d77-669a-4de6-82a1-3aef9f1694b3">


##smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.
<img width="373" alt="image" src="https://github.com/AsinVardhini/Enumeration/assets/119417735/f7b6ba74-7de6-435e-bd2c-1e601591710c">


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

<img width="416" alt="image" src="https://github.com/AsinVardhini/Enumeration/assets/119417735/5a06926a-d2ea-47ac-9c72-81fbbb6e82ba">


select any username in the first column of the above file and check the same

<img width="371" alt="image" src="https://github.com/AsinVardhini/Enumeration/assets/119417735/23c38c58-6deb-42bd-9994-08a80bcb5b51">


#Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands

  
 ##Output
 
<img width="369" alt="image" src="https://github.com/AsinVardhini/Enumeration/assets/119417735/f4dc26e9-3a89-483e-9fee-1e78e6579cb5">

  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:

<img width="416" alt="image" src="https://github.com/AsinVardhini/Enumeration/assets/119417735/657162b7-9229-44f0-942a-dc2e1dd8ea81">


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully
