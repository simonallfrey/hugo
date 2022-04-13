---
title: "$5/mo VPS on digitalocean with free domain name"
date: 2022-04-13T13:40:52+02:00
draft: false
---
### Getting a free domain name.

Wed Apr 13 09:51:38 2022

https://my.freenom.com/domains.php

google social sign in with simon.allfrey.france

trick: 
1. Search for desired domain name without top level domain, TLD, e.g. ".ga"
2. Do not click on the buttons on the right.
3. Search for the desired domain name with the TLD

We'll use Freenom as a registrar, but digitalocean's nameservers, the settings on Freenom are:

Services->My Domains->Manage Domain->Management Tools->Nameservers->Use Custom Nameservers  
NS1.DIGITALOCEAN.COM  
NS2.DIGITALOCEAN.COM  
NS3.DIGITALOCEAN.COM  

https://docs.digitalocean.com/products/networking/dns/how-to/manage-records/

LeftSideBar->Manage->Networking->Domains  
Add an 'A' record for  
dry-citadel.ga  
www.dry-citadel.ga  



