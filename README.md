# 🧠 Argon Manager – Plateforme de Gestion Éducative

Une application web Full Stack conçue pour la gestion complète d’un centre éducatif : revenus, paiements, enseignants, élèves, factures, statistiques — avec interface moderne et fonctionnalités dynamiques.

---

## 🌟 Aperçu du projet

**Argon Manager** permet à un centre de suivre tous les flux financiers et pédagogiques :  
- Confirmation et gestion des paiements des élèves  
- Calcul automatique des parts enseignants  
- Génération de factures imprimables  
- Suivi du revenu mensuel  
- Statistiques détaillées et interactives

---

## ⚙️ Technologies Utilisées

| Catégorie | Technologie |
|----------|-------------|
| 🎨 Frontend | React.js, Redux Toolkit, TailwindCSS |
| 🧠 Backend | Laravel 10, RESTful APIs |
| 🗃️ Base de données | MySQL |
| 🔐 Authentification | Sessions sécurisées, gestion de rôles |
| 📊 Statistiques | Filtres + Graphiques |
| 🧾 PDF | Génération de factures imprimables |

---

## 📂 Fonctionnalités Clés

- Authentification sécurisée par rôle (Admin / Enseignant / Élève)  
- Paiements et abonnements (statut, délais, alertes)  
- Génération de factures PDF + impression  
- Tableau de bord avec graphiques dynamiques  
- CRUD complet pour enseignants, sections, étudiants  
- Navigation fluide avec menu latéral  
- Responsive & mobile friendly

---

## 🧪 Aperçu Visuel *(médias aléatoires à remplacer)*

<p align="center">
  <img src="https://placehold.co/800x400?text=Login+Page" width="600"/>
  <em>Login page (à personnaliser)</em>
</p>

<p align="center">
  <img src="https://placehold.co/800x400?text=Dashboard+Statistiques" width="600"/>
  <em>Dashboard avec graphique des revenus</em>
</p>

<p align="center">
  <img src="https://placehold.co/800x400?text=Liste+des+Factures" width="600"/>
  <em>Factures avec options d'impression</em>
</p>

---

## 🎥 Vidéo de démonstration *(à ajouter plus tard)*

> 📹 *Lien vers une vidéo de démonstration ici (à venir)*  
> Exemple : `https://www.youtube.com/watch?v=demo_video`

---

## ⚙️ Installation Rapide

```bash
# Backend Laravel
cd backend
composer install
php artisan migrate
php artisan serve

# Frontend React
cd frontend
npm install
npm run dev
