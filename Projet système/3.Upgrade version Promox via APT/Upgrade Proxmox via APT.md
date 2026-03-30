# Documentaion sur l'upgrade du serveur Proxmox.  
### Pourquoi upgrade de la version 7.4 à 9.1 ?  
#### La raison est simple et embêtante : la carte contrôleur RAID PERC H200 installé physiquement dans le serveur et trop veille pour les paquets récents du kernel Linux.  
#### Il faut donc passer par APT (via le paquet réseau) pour avoir une version stable et plus sécurisé de Proxmox.
