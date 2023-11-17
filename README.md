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

If the IP You are searching is add on ip.bunker because is the second time you scan the same ip address.

Going to see a Warning Message, the IP address is not going to be add on **ip.bunker** because the ip address is already add it.

