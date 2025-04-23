# Supervision Web et Application Métier – Projet Contractuel

###  Objectif

Développer une **application web** pour **surveiller** et **remonter les données** d'une ligne de production automobile.

---

###  Aperçu de l'application web et de l'application bureautique
<img src="https://github.com/user-attachments/assets/4c04d072-b59d-42c7-baa3-9f9681c0a970" alt="Capture application web et desktop" width="600"/>

---

###  Étapes du projet

- **Maquettage de l’interface utilisateur**
- **Conception de la base de données**
- **Développement d’une application légère** avec le framework **Peewee**
- **Développement d’une application lourde** avec **Python + PyQt**
- **Communication par sockets Messaging** entre l’application de supervision et les équipements robotiques
- **Programmation machine** (TPE KAREL) sur **robot FANUC LR MATE**

---

### Communication entre Supervision et Robotique

Utilisation d’un **package Python** permettant la communication entre l’application de supervision et les robots industriels **FANUC**.

####  `fanucpy` – Package Python pour robots FANUC

Ce package est composé de deux parties :
- **Interface Python** pour envoyer et recevoir des données
- **Driver robotique** développé en **KAREL** et langage du **Teach Pendant** (pendant FANUC)

####  Schéma de communication
[![Communication Protocol](https://github.com/torayeff/fanucpy/raw/main/media/CommProtocol.png)](https://github.com/torayeff/fanucpy/raw/main/media/CommProtocol.png)
