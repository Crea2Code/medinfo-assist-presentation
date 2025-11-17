<p align="center">
  <img src="/medinfo-banner.png" alt="Crea2code MedInfo Assist banner" width="100%" />
</p>

<h1 align="center">

<svg xmlns="http://www.w3.org/2000/svg" width="34" height="34" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-brain-circuit w-16 h-16 text-blue-600 mb-4" aria-hidden="true"><path d="M12 5a3 3 0 1 0-5.997.125 4 4 0 0 0-2.526 5.77 4 4 0 0 0 .556 6.588A4 4 0 1 0 12 18Z"></path><path d="M9 13a4.5 4.5 0 0 0 3-4"></path><path d="M6.003 5.125A3 3 0 0 0 6.401 6.5"></path><path d="M3.477 10.896a4 4 0 0 1 .585-.396"></path><path d="M6 18a4 4 0 0 1-1.967-.516"></path><path d="M12 13h4"></path><path d="M12 18h6a2 2 0 0 1 2 2v1"></path><path d="M12 8h8"></path><path d="M16 8V5a2 2 0 0 1 2-2"></path><circle cx="16" cy="13" r=".5"></circle><circle cx="18" cy="3" r=".5"></circle><circle cx="20" cy="21" r=".5"></circle><circle cx="20" cy="8" r=".5"></circle></svg>  
MedInfo Assist 💙
</h1>

<p align="center">
  <b>L’IA qui simplifie le langage médical pour tous</b><br/>
  Développée par <a href="https://crea2code.fr" target="_blank">Sonia Chalal</a> | <b>Crea2Code</b> – Développeuse Full Stack & IA Web
</p>

<p align="center">
  <a href="https://medinfo-assist.vercel.app" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/🚀%20Live%20Demo-MedInfo%20Assist-2563EB?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo">
  </a>
  <a href="https://medinfo-assist-backend.onrender.com/docs" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/API%20Docs-FastAPI-success?style=for-the-badge&logo=fastapi" alt="FastAPI Docs">
  </a><br/><br/>
  <img src="https://img.shields.io/badge/Next.js-16.0.0-black?logo=nextdotjs" alt="Next.js" />
  <img src="https://img.shields.io/badge/FastAPI-Backend-success?logo=fastapi" alt="FastAPI" />
  <img src="https://img.shields.io/badge/TailwindCSS-Design-38B2AC?logo=tailwindcss" alt="TailwindCSS" />
  <img src="https://img.shields.io/badge/Python-3.13-blue?logo=python" alt="Python" />
  <img src="https://img.shields.io/badge/Groq-LLaMA3%2070B-orange?logo=groq" alt="Groq LLaMA3" />
</p>

---

## 📋 Sommaire
- [🌟 Présentation](#-présentation)
- [🎯 Bilan du déploiement cloud](#-bilan-du-déploiement-cloud)
- [🧠 Modèle d’IA & principes d’utilisation](#-modèle-dia--principes-dutilisation)
- [🎨 Aperçu du design](#-aperçu-du-design)
- [🧩 Stack technique](#-stack-technique)
- [🧠 Fonctionnalités principales](#-fonctionnalités-principales)
- [🌍 Version en ligne](#-version-en-ligne)
- [🖋️ Auteur](#️-auteur)
- [⚖️ Licence](#-licence)

---

## 🌟 Présentation

**MedInfo Assist 💙** est une application web d’intelligence artificielle qui rend le **langage médical accessible à tous**.  
Grâce à l’IA, elle :

- 🩺 **Explique** les termes médicaux complexes  
- 💡 **Fournit** des conseils de prévention santé personnalisés  
- 🤖 **Montre** la puissance de l’IA appliquée à la pédagogie médicale  

> Projet créé pour le **Forum Santé pour Tous 2025 – “IA et données de santé au service de l’innovation”** à Caen.

---

## 🎯 Bilan du déploiement cloud

| Composant | Technologie | Hébergeur | État |
|------------|--------------|------------|------|
| 🧠 Backend API | FastAPI (Python 3.13) | Render | ✅ En ligne |
| 💻 Frontend | Next.js 16 (React 19) | Vercel | ✅ En ligne |
| 🔑 Variables ENV | GROQ_API_KEY, NEXT_PUBLIC_API_BASE_URL | Configurées | ✅ OK |
| 🩺 Analyse IA | FastAPI + Groq | Fonctionnelle | 💬 Réponses instantanées |
| 💡 Vulgarisation médicale | IA + règles de sécurité | Fonctionnelle | 💬 Explications claires |

---

## 🧠 Modèle d’IA & principes d’utilisation

MedInfo Assist utilise le modèle open-source **LLaMA 3-70B** (développé par Meta), exécuté via la plateforme haute performance **Groq**, ce qui permet des réponses extrêmement rapides adaptées à l’usage interactif.

📌 Ce modèle est :
- un modèle IA **généraliste** (non spécialisé santé)
- utilisé pour **simplifier** et expliquer des contenus médicaux
- configuré avec **des garde-fous** pour rester dans un rôle éducatif

⚠️ **Important :**
- Ce projet n’est pas un dispositif médical
- Il ne fournit pas de diagnostic
- Il ne remplace pas un avis médical professionnel

---

## 🎨 Aperçu du design
Interface claire, fluide et rassurante, inspirée des plateformes médicales modernes.  
Logo **BrainCircuit 🧠** : symbole de la synergie entre intelligence humaine et artificielle.

<p align="center">
  <img src="/MedInfo-Assist-logo.png" alt="Crea2code MedInfo Assist banner" width="100%" />
</p>

---

## 🧩 Stack technique

| Domaine | Technologie | Description |
|----------|--------------|--------------|
| **Frontend** | Next.js 16 + TypeScript | Interface utilisateur moderne |
| **Backend** | FastAPI (Python 3.13) | API d’analyse IA |
| **IA** | Groq + LLaMA 3-70B | Inférence IA temps réel |
| **Design** | TailwindCSS | UI responsive |
| **Déploiement** | Render + Vercel | Architecture cloud |
| **Icons** | Lucide + SVG | Identité visuelle |
| **Versioning** | GitHub | CI/CD |

---

## 🧠 Fonctionnalités principales

- 🩺 Analyse IA des textes médicaux  
- 💡 Conseils santé vulgarisés  
- 🧾 Format Markdown lisible  
- ⚙️ Connexion directe Next.js ↔ FastAPI  
- 🎬 Animation d’accueil  
- ⚕️ Encadré explicatif et avertissement patient

---

## 🌍 Version en ligne

| Service | Lien |
|---------|------|
| 🚀 Frontend (Web App) | <a href="https://medinfo-assist.vercel.app" target="_blank" rel="noopener noreferrer">medinfo-assist.vercel.app</a> |
| 🧠 Backend API | <a href="https://medinfo-assist-backend.onrender.com" target="_blank" rel="noopener noreferrer">medinfo-assist-backend.onrender.com</a> |
| 📘 API Docs (Swagger) | <a href="https://medinfo-assist-backend.onrender.com/docs" target="_blank" rel="noopener noreferrer">/docs</a> |

---

## 🖋️ Auteur

👩‍💻 **Sonia Chalal**  
Fondatrice de **Crea2Code – Agence Digitale & Formations**  
💬 Passionnée par la pédagogie numérique, l’IA et la santé connectée.  
📍 Rouen, France  
 - 🔗<a href="https://www.crea2code.fr" target="_blank" rel="noopener noreferrer"> Crea2Code</a> 

 - 🔗<a href="https://www.linkedin.com/in/sonia-chalal-46a16b1bb/" target="_blank" rel="noopener noreferrer"> LinkedIn</a> 

---

## ⚖️ Licence

Projet distribué sous licence **MIT**  
© 2025 – **Crea2Code | Sonia Chalal**

<p align="center">
  <img src="https://img.shields.io/badge/Version-2.2-blue?style=for-the-badge" alt="version" />
</p>
