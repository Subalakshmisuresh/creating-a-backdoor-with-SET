# Creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

![image](https://github.com/Poojithamanohar/creating-a-backdoor-with-SET/assets/119423592/42d3b894-22d7-4853-b7f9-4b7a17ffac5a)

It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/Poojithamanohar/creating-a-backdoor-with-SET/assets/119423592/73ba84a8-fb45-4a65-b820-ea45614b88e4)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/Poojithamanohar/creating-a-backdoor-with-SET/assets/119423592/36d4848f-87c7-4902-9e24-753cceb3c2d5)
The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![image](https://github.com/Poojithamanohar/creating-a-backdoor-with-SET/assets/119423592/8eb88607-f756-4537-a38d-ed95009aee46)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![image](https://github.com/Poojithamanohar/creating-a-backdoor-with-SET/assets/119423592/75b5cc32-fdd9-4f35-b8d4-e9e775d0b270)
It shows the following screen in which the option Google can be selected:
![image](https://github.com/Poojithamanohar/creating-a-backdoor-with-SET/assets/119423592/5082ef0c-bf90-4edb-905b-ef23e0d0b553)
SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/Poojithamanohar/creating-a-backdoor-with-SET/assets/119423592/b0a51363-c3f4-4d6b-8f3c-21a184b2754b)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/Poojithamanohar/creating-a-backdoor-with-SET/assets/119423592/b2cceb60-e2e7-4731-8c05-b95ee1c256d8)
SET logs the information regarding the Google credentials:
![image](https://github.com/Poojithamanohar/creating-a-backdoor-with-SET/assets/119423592/53a38d5b-fc37-47ad-93c4-ec96b48aab70)
SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/Poojithamanohar/creating-a-backdoor-with-SET/assets/119423592/974ca92b-d0f2-4091-b443-2cc4b40b63b7)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
