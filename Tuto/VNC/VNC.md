# VNC server

## Objectifs

* Afficher le GUI du raspberry pi sur son PC
* Pouvoir utiliser son clavier et sa souris comme entrée

## Tutoriel

### Raspberry

#### Installer VNC

sudo apt update  
sudo apt install realvnc-vnc-server realvnc-vnc-viewer -y

#### Activer VNC

sudo raspi-config  
**Interface options** --> **VNC** --> **yes**

### PC

Installer VNC viewer --> [RealVNC](https://www.realvnc.com/fr/connect/download/viewer/)

## Utiliser

* Rentrer l'adresse IP du Raspberry pi
* Mettre son login/password
