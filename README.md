# Générateur `autounattend.xml`
> https://autounattendxml.pages.dev/

Cette page web permet de générer automatiquement un fichier **`autounattend.xml`** pour l’installation automatisée de **Windows 10 / 11**.  
Elle fournit une interface simple et claire pour configurer :

- 📦 **Version & édition de Windows** (10 ou 11, Home, Pro, Enterprise, etc.)  
- 🔑 **Clé produit** ou index d’image  
- 🌐 **Langue, clavier et fuseau horaire**  
- 👤 **Comptes utilisateurs et options OOBE** (création d’un compte local, activation de l’Administrateur, autologon…)  
- 💾 **Mode d’installation disque** (GPT, MBR ou partition disponible)  
- 🔒 **Paramètres de confidentialité et télémétrie** (désactivation des pubs, télémétrie minimale, etc.)  
- ⚙️ **Exécution automatique d’un script PowerShell** via `FirstLogonCommands`  

L’outil propose ensuite :  

- ✨ Génération immédiate du XML  
- 📥 Téléchargement direct du fichier `autounattend.xml`  
- 📋 Copie dans le presse-papiers  
- 🔄 Réinitialisation des paramètres  

> ⚠️ **Attention** : Les modes GPT/MBR effacent entièrement le disque 0 et recréent les partitions. À utiliser avec prudence.  

---

## Démo

Il suffit d’ouvrir la page `index.html` dans un navigateur moderne (Chrome, Edge, Firefox…) pour commencer à générer votre fichier.  
Aucune installation n’est nécessaire, tout se fait en **local**.  

---

## Auteur

👤 Développé par [@azlord200](https://github.com/azlord200)  
