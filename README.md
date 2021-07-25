# Glusterfs-os-Ubuntu 
# [Type de Volume GlusterFs : Répliqué, 3 noeuds]
Ce code ansible est le déploiement du systeme de stockage distribué Glusterfs avec type de volume répliqué comme pool de stockage pour un cluster swarm composé de 3 noeuds tous des managers

## Pre-requis

* Os Linux Ubuntu à partir de 18.04
* Ansible installé sur votre machine

## Comment utilisé le projet ?

* Vous devez cloner le projet : git clone https://github.com/enassar225/glusterfs-os-ubuntu.git
* Renseignez les adresses ip & le nom de vos noeuds, modifiez si besoin les noms des variables
* Renseignez les infos pour le fichier inventory
* Lancez votre playbook : ansible-playbook -i inventory.yml task/installation.yml

## Sources

* https://gluster.readthedocs.io/en/latest/Install-Guide/Install/#for-ubuntu
* https://github.com/gluster/gluster-ansible-infra pour le role infra
* https://github.com/gluster/gluster-ansible-cluster pour le role cluster

