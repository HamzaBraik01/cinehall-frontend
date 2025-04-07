# 🎬 CinéHall Frontend

Bienvenue dans le projet frontend de **CinéHall**, une application moderne et responsive permettant aux utilisateurs de consulter des films, réserver des sièges et gérer leurs billets de cinéma de manière intuitive. Cette application consomme l'API CinéHall et est développée en **JavaScript natif**.

---

## 📋 Description du projet

Suite au développement de l’API CinéHall, ce frontend vise à offrir une expérience utilisateur fluide et ergonomique pour :
- Consulter les films et leurs séances disponibles 🎥
- Réserver et payer des places en ligne 🪑
- Télécharger des billets avec QR Code 🎟️
- Gérer son profil et ses réservations 👤

---

## 🎯 Objectifs

Développer une application frontend qui :
- Est **responsive** et adaptée à tous les appareils
- Offre une interface **moderne** et intuitive
- Consomme efficacement l’API CinéHall

---

## ✨ Fonctionnalités

### 👤 Gestion des utilisateurs
- **Inscription et connexion** via JWT 🔑
- **Modification du profil** utilisateur ✏️
- **Suppression de compte** 🗑️
- **Affichage des informations personnelles** ℹ️

### 🎞️ Consultation des films & séances
- Liste des films avec détails (titre, description, image, durée, genre, âge minimum) 📜
- **Bande-annonce intégrée** ▶️
- Liste des séances par film ⏰
- Détails des séances (date, heure, type : Normal/VIP, langue) 🕒
- Filtrage par type de séance (Normal / VIP) 🔍

### 🪑 Réservation de sièges
- Visualisation de la salle (sièges disponibles/occupés) 🗺️
- **Sélection de sièges** ✅
- Gestion des sièges couple (réservation automatique de 2 sièges) 💑
- Affichage du **prix total** selon les sièges 💰
- Alerte d’expiration après **15 minutes** ⏳
- Statut de la réservation (réservé, payé, expiré) 📈

### 💳 Paiement
- Simulation d’un système de paiement (Stripe, PayPal ou interface fictive) 💳
- Validation et confirmation du paiement ✔️
- Mise à jour du statut après paiement 🔄

### 🎟️ Billet électronique
- Affichage du billet avec toutes les informations 📄
- Génération et affichage d’un **QR Code** 📲
- Téléchargement du billet en **PDF** ⬇️

### 📁 Espace utilisateur
- Liste des réservations (passées et actuelles) 📋
- Téléchargement des billets 🎫
- Annulation ou modification des réservations ❌

---

## 🚀 Installation
- Clonez le dépôt :
git clone https://github.com/HamzaBraik01/cinehall-frontend.git