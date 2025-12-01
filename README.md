# 🎓 Plateforme de Gestion - Amicale du Ministère de l'Éducation

[![React](https://img.shields.io/badge/React-18.3-blue?logo=react)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-5.4-646CFF?logo=vite)](https://vitejs.dev/)
[![Laravel](https://img.shields.io/badge/Laravel-12.0-FF2D20?logo=laravel)](https://laravel.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-38B2AC?logo=tailwind-css)](https://tailwindcss.com/)
[![Ant Design](https://img.shields.io/badge/Ant%20Design-5.22-0170FE?logo=ant-design)](https://ant.design/)

> **Note Importante :** Ce dépôt contient uniquement la documentation et la démonstration du projet. Le code source est la propriété de la société **TAC-TIC** et reste confidentiel.

---

## 📺 Démonstration

Voici une vidéo de démonstration de l'application (environnement local) présentant les fonctionnalités que j'ai développées et intégrées :

[![Regarder la démo sur YouTube](https://img.youtube.com/vi/TON_ID_VIDEO_ICI/maxresdefault.jpg)]([TON_LIEN_YOUTUBE_ICI](https://youtu.be/Wx8lNIoo-Ms))

*(Cliquez sur l'image ci-dessus pour voir la vidéo)*

---

## 📋 Contexte du Projet

Ce projet a été réalisé dans le cadre de mon **Projet de Fin d'Année (PFA)** lors d'un stage de 2 mois chez **TAC-TIC**.

Il s'agit d'une application web complète (SPA) destinée à la gestion des services sociaux de l'Amicale du Ministère de l'Éducation. J'ai rejoint une équipe active pour contribuer au développement, à la refonte et à l'optimisation de plusieurs modules clés de la plateforme.

---

## 🚀 Mes Contributions

Durant ce stage, j'ai travaillé sur l'architecture Frontend (React) et Backend (Laravel API). Voici mes réalisations principales :

### 1. Refonte et Migration (Legacy vers React)
J'ai assuré la migration de plusieurs interfaces initialement développées en HTML/CSS/Bootstrap/JS natif vers une architecture moderne **React.js**.
- Pages migrées : `Home Page`, `Historique`, `Pages Conventions`, `Contact`.
- Intégration de composants réutilisables et nettoyage du code legacy.

### 2. Développement de Modules Fonctionnels
- **Gestion des Conventions :** Développement complet du module (Backend & Frontend) permettant de gérer les conventions nationales, régionales et avec les opérateurs téléphoniques.
- **Espace Adhérent :** Création du tableau de bord personnel pour les membres (suivi des demandes, profil).
- **Espace Fournisseur :** Développement d'un espace dédié pour les partenaires permettant la gestion de leurs offres et interactions avec l'amicale.

### 3. Maintenance et Amélioration
- **Module Résidences & Hôtellerie :** Correction de bugs critiques et optimisation du flux de réservation.
- **Internationalisation (i18n) :** Vérification et correction intégrale des traductions (Français 🇫🇷 / Arabe 🇹🇳) pour assurer le support RTL (Right-to-Left) et une expérience utilisateur fluide.

---

## 🛠️ Stack Technologique

Le projet repose sur une architecture moderne séparant le Frontend et le Backend via une API RESTful.

### 🎨 Frontend (SPA)
| Catégorie | Technologies |
|-----------|--------------|
| **Core** | React 18, Vite |
| **Styling & UI** | Tailwind CSS, Ant Design (Pro Components), Lucide React |
| **State Management** | Redux Toolkit, Redux Thunk |
| **Routing & HTTP** | React Router DOM 7, Axios (avec Interceptors) |
| **Internationalisation** | i18next, react-i18next (FR/AR) |
| **Outils** | Leaflet (Cartes), Swiper (Carrousel), Dayjs |

### 🏗️ Backend (API REST)
| Catégorie | Technologies |
|-----------|--------------|
| **Framework** | Laravel 12 (PHP 8.2+) |
| **Base de données** | MySQL 8 |
| **Authentification** | Laravel Passport (OAuth2) |
| **Architecture** | Repository Pattern |
| **Permissions** | Spatie Laravel Permission (RBAC) |
| **Features** | QR Codes, PDF Generation (DomPDF), Excel Export |

---

## 🔐 Sécurité et Architecture

Le projet implémente des standards de sécurité robustes :
* **Authentification JWT :** Gestion sécurisée des sessions via Tokens.
* **Role-Based Access Control (RBAC) :** Système de permissions granulaire (Super Admin, Fournisseur, Membre, Bureaux Régionaux).
* **Route Guards :** Protection des routes Frontend (`AuthGuard`, `PermissionGuard`).
* **Validation :** Validation stricte côté client (Ant Design Forms) et côté serveur (Laravel Request Validation).

---

## 👤 Auteur

**Mahdi Boughariou**
* Étudiant en 3è année ingénierie - Génie Logiciel


---

*Ce README documente mon travail effectué durant la période de stage et ne contient aucun code source propriétaire.*
