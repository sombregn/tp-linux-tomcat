# Nom et Prenom: BAH Alpha Souleymane 
# 🚀 Linux, Vagrant, TomCat

Ce projet vise a mettre en place un env linux provisioner depuis vagrant via des conn ssh.
1. Intaller une machine Virtual via Vagrant sous linux
2. Installer un serveur TomCat

---


## 🎯 Objectif
L'objectif de ce projet est de créer une VM via vagrant et installer un serveur tomCat.

---

## 📦 Prérequis
Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- **VirtualBox** (Pour la VM) ou tout autres ... 
- **Vagrant** (Pour la gestion de la VM)
- **Git Bash** (Pour exécuter les commandes plus facilement sous Windows) ou autres **PowerShell** etc

---


### 1. Créer un dossier de travail
- **mkdir le nom que vous  voulez**
- **Par exemple: mkdir vagrant-linux**
-**cd nom creer**
- **Par exemple: cd vagrant-linux**
 
 ### 2. Setup du VagrantFile 
 Ajouter le fichier Vagrantfile
- **cmd> vagrant init**
- **Un file vagrant vous sera initialisé automatiquement dans ce file vous travailler.**

### 3. Validation du Vagrant file
-**cmd> vagrant validate**

### 4. Démarrage du Vagrant File:
-**cmd> vagrant up**

### 📌 Ce que fait cette commande :
- **Télécharge l’image Ubuntu 20.04 ou selon la version précisé si elle n’existe pas encore.**
-**Crée et configure la VM.**
-**Installe Tomcat.**

### 🎯 Vérifications après l’installation
**-🔗 1. Se connecter à la VM via SSH**
-**cmd> vagrant ssh**

### 📌 Conclusion**
-**✅ Nous avez maintenant une machine virtuelle sous Ubuntu 20.04 avec un Serveur Tomcat**
-**📝 Remarque**
-**Voir toutes captures dans le dossier captures**

![verifVitralBox](https://github.com/user-attachments/assets/4df69680-8dce-427a-bc49-3387f9280418)
![verifSetupVagrant](https://github.com/user-attachments/assets/9aad4866-fec6-4584-a441-6efa61136d11)
![validateSucessVagrant](https://github.com/user-attachments/assets/1507ebe5-59fe-44c7-933a-9f5cc9626155)
![setupVagrant](https://github.com/user-attachments/assets/bf13aa96-b904-47bf-b824-eb0da6b5bc90)
![createVMfinal](https://github.com/user-attachments/assets/a7b9fbd2-37ac-4bda-bff8-bb5f8d5c7835)
![createVm1](https://github.com/user-attachments/assets/53adf460-9e12-4845-9837-2ad6064d7234)
![apreCreationVM](https://github.com/user-attachments/assets/9ddb7e1d-3fac-4e32-9e5b-2a7eb276d6b0)


