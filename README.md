# Logixee-Buisness-Processes
Mini projet académique du module Processus Métiers en Master 2 DATASCALE à l'université de Versailles Saint Quentin En Yvelines qui est réalisé avec Java BPEL.
Encadré par Mr Taher YEHIA.

## Sujet de projet
Le projet parle initialement sur une entreprise qui fournis des services dans le monde de 
transport dont les clients sont, soit des particuliers, soit des entreprises, PME et grands comptes.
Le sujet de projet se situe ici:
[Sujet Logixee](./Report/M2Datascale_TP2_BPM.pdf) 

## Pré-requis
Pour assurer le bon fonctionnement du code réalisé et permettre sa compilation, un certain nombre d'outils et de bibliothèques doivent être présents sur la machine.

Pour obtenir le projet il suffit de le cloner avec la commande :
`git clone https://github.com/GT17S/Logixee-Buisness-Processes.git`

### IDE Java (Eclipse, Intellij Idea, NetBeans ...)
On vous recommande de télécharger un IDE de votre choix parmi ses derniers il y'a : <br>
`Eclipse` sur le site [Télécharger Eclipse Java IDE](https://www.eclipse.org/downloads/)
<br>`Intellij Idea` sur le site [Télécharger Intellij Idea IDE](https://www.jetbrains.com/fr-fr/idea/download/).
<br>Et cela afin de lancer le code réalisé.

### BPEL 
Après le téléchargement un IDE de votre choix et son installation, vous aurez besoin de télécharger BPEL pour faire orchestrer et faire marcher les processus métiers 
[Apache BPEL](https://www.oracle.com/fr/middleware/technologies/soasuite/downloads.html). 

### ODE
ODE est un logiciel codé en Java en tant que moteur de workflow pour gérer les processus métier qui ont été exprimés dans le Web Services BPEL via un site Web.
[Apache ODE](https://ode.apache.org/getting-ode.html)

## Quelques précisions
#### Diagramme UML
Apres l'interprétation du sujet, on se retrouve à établir un diagramme UML suivant pour les differents services proposés pour la societé 
Logixee, avec les differents flux existants entre les clients et les services.
![Diagramme des flux](./Report/logixee%20uml.pdf)

#### Processus Métier
Apres l'interprétation du diagramme UML, on se retrouve à établir un processus métiers sur BPEL, pour les differents services proposés pour la societé Logixee. 
![Bpel Process](./Report/BPEL%20%20process.pdf)

#### Cahier de charges du projet
Pour plus d'informations sur ce projet, que çà soit sur coté conception et choix de services, tout est expliqué en details dans ce cahier de charges. 
Je vous invites à le lire [cahier de charges](./Report/Bpel%20TP%20LOGIXEE.pdf).

Et vous en trouvez une petite manipulation sur les differents fichiers WSDL sur l'outil BPEL et ODE.

#### Fichiers Joints
Vous trouverez ici les fichiers joints, soit en java qui ont permis d'avoir les fichiers WSDL en passant par Axis 2 d'Apache Tomcat pour les transformés en services web, et en executable (.wsdl) pour SoapUI.
<br>[Java Files](./Java%20Source%20Files)  
[Wsdl Files](./Wsdl%20Used%20Files)
<br>[Projet du BPEL à lancer pour avoir les résultats](./LogixeeEnd)
