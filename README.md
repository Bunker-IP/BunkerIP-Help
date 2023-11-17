![alt text](https://dnsbl.evilnet.org/assets/img/bunker-ip-small-logo.png)

# Bunker-[IP] How to Guide Documentation.

## Main Menu

![alt text](https://raw.githubusercontent.com/Bunker-IP/BunkerIP-Help/main/bunker-img/MainMenu.jpg)

In this Main Menu, you can check all options available with Bunker-[IP]. 
You can select a number to run the script in the section you need it.

```
cd BunkerIP
sh bunker.sh
```

**NOTE:** Recomendation to run the script for Firewall and Web Server: **sudo** privileges.

**NOTE:** Bunker-[IP] all script is on a directory named: **BunkerIP**


## Bunker-[IP] MENU

![alt text](https://raw.githubusercontent.com/Bunker-IP/BunkerIP-Help/main/bunker-img/BunkerIP-Menu.JPG)

In this section you can use Bunker-[IP] RBL Security System.

You can Search IP Address on a list of RBL.

Add a new RBL Domain in your **rbl-list.bunker**

You can check the RBL List to make sure all is correct.

Can update all the time this **rbl-list.bunker** with Add and Delete URL RBL.

Check all the IP Address you got add in **ip.bunker** with a RBL Match or Manual adding.


## Bunker-[IP] - SEARCH

![alt text](https://raw.githubusercontent.com/Bunker-IP/BunkerIP-Help/main/bunker-img/BunkerIP-search.JPG)

You can search a IP for a positive match in some RBL add on the **rbl-list.bunker**

If the IP Got a positive result on a RBL Domain, going to be add it in **ip.bunker**

Bunker-[IP] don't add duplicate match or duplicate manual adding.

![alt text](https://raw.githubusercontent.com/Bunker-IP/BunkerIP-Help/main/bunker-img/BunkerIP-Search-NO-Duplicate.JPG)

**NOTE:** If the IP You are searching is add on ip.bunker because is the second time you scan the same ip address.

**NOTE:** Going to see a Warning Message, the IP address is not going to be add on **ip.bunker** because the ip address is already add it.

**NOTE:** If the ip address you scan got a vhost/domain name, is going to show in result. **Remember:** Only IP Address are adding on RBL System for better results.


## Bunker-[IP] - Add URL BRL in Bunker

![alt text](https://raw.githubusercontent.com/Bunker-IP/BunkerIP-Help/main/bunker-img/BunkerIP-Add-RBL-Domain.JPG)

**NOTE:** This command add a new RBL Domain in the **rbl-list.bunker** This list don't add duplicate domains RBL.


![alt text](https://raw.githubusercontent.com/Bunker-IP/BunkerIP-Help/main/bunker-img/BunkerIP-Add-RBL-Domain-NO-Duplicate.JPG)

**NOTE:** If the RBL Domain is add in **rbl-list.bunker** going to display a message info.

**NOTE:** In case you want to remove the RBL Domain from **rbl-list.bunker** You can do it very easy.

**REMEMBER:** if you remove a RBL Domain from **rbl-list.bunker** the script for RBL not going to search the IP in that Domain.

![alt text](https://raw.githubusercontent.com/Bunker-IP/BunkerIP-Help/main/bunker-img/BunkerIP-Delete-RBL-Domain.JPG)

**NOTE:** This option can be use on RBL who are not working and want to remove from **rbl-list.bunker**

## Bunker-[IP] - Bunker Display All the IP in **ip.bunker**

![alt text](https://raw.githubusercontent.com/Bunker-IP/BunkerIP-Help/main/bunker-img/BunkerIP-IP-Bunker-LIST.JPG)

**NOTE:** This Command show all the IP Address listed in **ip.bunker** DB this list is from a positive RBL Match or Manual Add

## Bunker-[IP] - Check Display Bunker RBL List

![alt text](https://raw.githubusercontent.com/Bunker-IP/BunkerIP-Help/main/bunker-img/BunkerIP-Check-RBL-List.JPG)

**NOTE:** This list display is from **rbl-list.bunker** Where all RBL Domain are add.




