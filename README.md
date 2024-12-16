## QUETE LVM

## Installation initiale LVM sur Debian.  

![LVM](LVM/1-LSBLK.png)  

## Ajout d'un disk sdb.  

![LVM](LVM/2-AjoutDisk.png)  

## Formatage du disk en partition LVM.  

![LVM](LVM/3-FDISK.png)  

## Création du volume physique.  

![LVM](LVM/4-PVCREATE.png)  

## Ajout du nouveau volume au volume vg-debian.  

![LVM](LVM/5-VGEXTEND.png)  

## Affichage du résultat (le volume totale est passé de 20G à 40G).  

![LVM](LVM/5-VGDISPLAY.png)  

## Création d'un snamp de /home.  

![LVM](LVM/7-SNAP.png)  

## Montage du snamp sur /home-snap.    

![LVM](LVM/8-MOUNT.png)  

## Résultat du montage.    

![LVM](LVM/9-LSBLK2.png)  

## Bye bye snap !  

![LVM](LVM/10-LVREMOVE.png)  


