# Installation de Proxmox sur un serveur Dell PowerEdge R810  
## Pour les besoins de la doc l'installation a été réalise sur une VM donc l'adressage IP, le volume du disque, mot de passe etc diffèrent de l'infrastructure.  
### Prérequis :
  Clé bootable sur Proxmox v7.4 (version ancienne car carte contrôleur RAID trop ancienne pour les paquets du kernel Linus récent)

### Place à l'installation :  
#### Après que le serveur ai booté sur la clé l'installateur Proxmox affiche ceci :   

![](1.installation_proxmox.png)

### Cliquez sur "Install Proxmox VE"  

----

### Puis acceptez les conditions générales d'utilisation : 

![](1.accepter_term.png)  

---

### Suite à cela il vous est demandé de choisir le disque d'installation : 

![](1.choisir_disque.png)

---

### A présent le choix de la langue/fuseau horaire/disposition du clavier est demandé :  

![](1.choisir_langue.png)  

---

### L'étape précédente effectué il faut a présent définir un mot de passe fort et une adresse email :  

![](1.définir_mdp.png)

---

### Viens après le moment d'attribuer une adresse IP au serveur :  

![](1.ip_fqdn.png)  

---

### Après avoir réalisé toutes ces étapes un sommaire de l'installation est affiché :  

![](1.cr_dl.png)  

---

### Appuyez sur "Install" et attendre :  

![](1.makesysboot.png)  
![](1.installation_ok.png)  

# L'installation désormais finie passons à la configuration du serveur Proxmox !  
