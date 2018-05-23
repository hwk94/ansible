# ansible
première tâches d'automatisation 

Ce projet a pour but de se familiariser avec l'outil Ansible et d'automatiser quelques tâches récurrentes des administateurs
tel que la mise à jour des paquets, l'installation d'outil (ici on htop, tshark et tcpdump) ainsi que la configuration du 
fichier resolv.conf.

Nous avons effectués ces test sur un parc de trois machines qui démontre la puissance et le gain de temps car toute ces 
tâches vont s'executer par le lancement du playbook-nodes.yml qui utiliser les roles et les variables pour mener ces actions a bien.


Sur un parc important de type entreprise, Ansible peut se relever très utile pour le déploiement d'équipement (on peut imaginer 
un système plug & play de switch qui pourrait récupérer sa coniguration selon l'endroit dans lequel ceci se trouverait).
