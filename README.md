# SAE502
SAE502 - Piloter un projet Informatique  

Ce projet GNS3 vise à mettre en place une architecture réseau composée de trois réseaux distincts : SR1 (v1), SR2 (v2) et SR3 (v3).  
Les machines de ces trois réseaux obtiennent ensuite leurs addresses IP grâce à un serveur DHCP.   

Prérequis :  
GNS3 installé et configuré.  
Image du routeur choisi : c7200 pour les versions v1, v2, v3 et c3745 pour les versions v4 et v5  
Description de l'architecture:  
![gns3 drawio](https://github.com/user-attachments/assets/b640fe6a-480e-48d7-9895-ac9530991753)

L'architecture a été décomposé en 5 versions :  

v1 : consiste en la réalisation du squelette du réseau SR1 (m1, m2, mA et mB)  
v2 : consiste en la réalisation du squelette du réseau SR2 (m3, m4, mC et mD)  
v3 : consiste en la réalisation du squelette du réseau SR3 (m5, m6, mF et mE)  
v4 : consiste en la réalisation du serveur dhcp pour effectuer l'addressage uniquement aux machines du réseau SR1  
v5 : addressage pour les deux autres réseaux, toujours par DHCP.  

Ce projet a été fait par :  
Mussa MIRZA - Chef de projet  
Catarino Manuel FRANCISCO - Lead Dev  
Gihed BOUGUERBA  
Fabiano BOBEICA  
