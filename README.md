# MineWatch 

🚀 Projet Minecraft en Java et Electron

Ce projet a pour objectif de développer une application permettant de gérer et surveiller un serveur Minecraft à l'aide d'un plugin personnalisé. L'application utilise à la fois le langage de programmation Java et le framework Electron pour offrir une interface utilisateur conviviale.

## Fonctionnalités

- 🔌 **Installation du plugin**: L'application facilite l'installation et la gestion du plugin sur le serveur Minecraft.
- 🎧 **Écoute des événements**: Une fois le plugin installé, il écoute les événements qui se produisent sur le serveur, tels que les connexions des joueurs, les commandes exécutées, les actions des joueurs, etc.
- 💾 **Enregistrement des données**: Les événements capturés sont enregistrés dans une base de données MongoDB pour une utilisation ultérieure.
- 📚 **Lecture des données**: L'application écoute continuellement la base de données MySQL pour récupérer les nouvelles données enregistrées.
- 📋 **Affichage des logs**: Les données récupérées sont affichées sous forme de tableau dans l'application, offrant ainsi une vue claire et organisée des activités du serveur Minecraft.

## Technologies utilisées

- ☕ **Java**: Utilisé pour développer le plugin Minecraft, qui s'intègre au serveur.
- ⚡ **Electron**: Utilisé pour créer l'application de surveillance, fournissant une interface utilisateur multiplateforme.
- 🍃 **MySQL**: Utilisé comme système de gestion de base de données pour enregistrer les événements du serveur Minecraft.

## Avantages

- 🔍 **Surveillance centralisée**: L'application fournit une solution pratique pour surveiller un serveur Minecraft à partir d'une application externe, offrant un contrôle centralisé et une vue d'ensemble des activités.
- 📊 **Analyse des données**: Les données enregistrées dans la base de données permettent d'effectuer des analyses ultérieures, de suivre les tendances et de détecter les problèmes éventuels.
- 💡 **Interface utilisateur conviviale**: L'interface utilisateur développée avec Electron offre une expérience utilisateur intuitive et réactive, facilitant la navigation et l'utilisation de l'application.

N'hésitez pas à personnaliser ce projet en fonction de vos besoins spécifiques et à explorer davantage les fonctionnalités possibles pour améliorer la surveillance de votre serveur Minecraft. Bien-sûr les changements sont accompagnés d'un pull request sur mon plugin car mon projet possède une license (Copyright).

Fini le : XX/XX/XXXX
