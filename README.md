# Personal-VPN
Personal VPN (OPEN VPN) Scripte Panel For Start a Personal VPN 

**Setting up personal filtering server**
## 1) Buy a virtual server :
To get started, you need to buy a VPS with Centos 7 x86 (or) Centos 7 x64 operating system.
> You can buy VPS from [Parspack website](https://parspack.com/vps)

## 2) Install **putty** software
Next step, you need a terminal emulator software to connect to a Linux server
>  [software download](https://soft98.ir/internet/network/3197-putty.html)

Login to the server with putty software and run the following command:
```
cd /tmp/ && yum install git -y && git clone https://github.com/pouyapazhoohandeh/Personal-VPN.git && cd Personal-VPN/ && sed -i -e 's/\r$//' centos7.sh && chmod 755 centos7.sh && ./centos7.sh
```
**The following commands to add a user to the server:**
>**useradd** : for Add a New User

>**passwd** : for set a password

useradd [username] - passwd [username]
*** 
And finally, visit our website [Picomedia Group](https://picomedia.ir) | [My Website](https://pouyapazhoohandeh.ir)
