# creating-a-backdoor-with-SET
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

![image](https://github.com/user-attachments/assets/a1cf636b-4908-4793-b8e4-7e229e5e1a2e)


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

![image](https://github.com/user-attachments/assets/a952a809-11b6-4f27-90db-6853112dfc80)

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/user-attachments/assets/61dac49f-99cc-4991-bc94-c824ffdc1392)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/user-attachments/assets/14a54896-36f1-478f-a354-1ebc2be5a634)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/user-attachments/assets/5f2dd2a2-958b-4ece-bf48-8cf6c18a7392)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/user-attachments/assets/65eb4483-39fc-4199-af35-38f83e9e1bde)

It shows the following screen in which the option Google can be selected:

![image](https://github.com/user-attachments/assets/d83f93c6-0e66-4828-b0ac-177a2d40b548)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/user-attachments/assets/14817d35-2d99-4214-801d-f965d6809b80)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/user-attachments/assets/a4ef95a2-971c-496d-8676-1d9b231a49bb)

SET logs the information regarding the Google credentials:

![image](https://github.com/user-attachments/assets/ab2b5e4a-007e-4a74-a148-54cbb06e10b9)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/user-attachments/assets/b3d8f86c-1cd9-4421-8286-5aa6efa0254e)










## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
