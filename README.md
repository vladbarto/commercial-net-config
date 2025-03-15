# Commercial network configuration project

## Agenda
1. Problem statement
2. Evolution

## 1. Problem Statements

[Tema 2][RO] Se consideră o clădire comercială cu 3 nivele. Se va folosi adresa de rețea 172.16.0.0/16 pentru rețeaua intranet, adresa de rețea 210.1.1.64/27 pentru DMZ și adresa 
de rețea 210.1.1.32/27 pentru accesul în exterior. Se vor proiecta 4 VLAN-uri (unul pentru fiecare etaj și unul pentru traficul de management). Pentru configurarea VLAN-urilor 
se va folosi protocolul VTP. Prin cablarea și configurarea rețelei se va asigura redundanța. Adresele hosturilor vor fi alocate dinamic folosind un singur server de DHCP aflat 
în VLAN-ul corespunzător primului etaj. Numărul minim de utilizatori deserviți de către fiecare VLAN este 200. Serverele de HTTP, FTP, DNS și MAIL vor fi plasate în DMZ și vor avea 
adrese publice. Numele domeniului web va include numele studentului. Pentru asigurarea conectivității se vor configura rute statice. Accesul în exterior se va realiza folosind NAT 
pe routerul care controlează DMZ, pe următorul interval de adrese publice: 210.1.1.35-210.1.1.62. 

Conectarea la ISP se va realiza printr-o interfață de tip Ethernet având adresa 210.1.1.34/27. Adresa ISP-ului este 210.1.1.33/27. Rețeaua Internet se va simula prin intermediul 
unui server și a unui calculator. 

Pentru securizarea echipamentelor de rețea se vor realiza următoarele configurări: 
- se vor defini utilizatori pe diferite nivele de privilegiu;
- criptarea parolelor;
- configurarea remote se va face doar prin ssh;
- se va securiza protocolul VTP.

Se vor prezenta și implementa două măsuri suplimentare de securizare a rețelei.

[EN] Consider a commercial building with 3 levels. The network address 172.16.0.0/16 will be used for the intranet network, the network address 210.1.1.64/27 for the DMZ, 
and the network address 210.1.1.32/27 for external access. Four VLANs will be designed (one for each floor and one for management traffic). 
VTP protocol will be used for VLAN configuration. The network cabling and configuration will ensure redundancy. Host addresses will be dynamically allocated using a single DHCP 
server located in the VLAN corresponding to the first floor. The minimum number of users served by each VLAN is 200. HTTP, FTP, DNS, and MAIL servers will be placed in the DMZ 
and will have public addresses. The web domain name will include the student's name. Static routes will be configured to ensure connectivity. External access will be achieved using NAT 
on the router that controls the DMZ, within the following public address range: 210.1.1.35-210.1.1.62. 

Connection to the ISP will be made through an Ethernet interface with the address
210.1.1.34/27. The ISP's address is 210.1.1.33/27. The Internet network will be simulated through a server and a computer. 

To secure the network equipment, 
the following configurations will be made: 
- users will be defined at different privilege levels;
- passwords will be encrypted;
- remote configuration will only be done via SSH;
- the VTP protocol will be secured.

Two additional network security measures will be presented and implemented.

## 2. Evolution
<img width="640" alt="image" src="https://github.com/user-attachments/assets/c8e27936-a150-4538-94ef-f5c2e563fb28" />
<img width="783" alt="image" src="https://github.com/user-attachments/assets/139045aa-d9a0-4a34-945c-0314a2b787be" />
