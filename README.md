# 🎓 SchoolWebApp

Une application web complète pour la gestion des étudiants, construite avec **ReactJS**, **FastAPI**, et **MySQL**.

---

## 🚀 Fonctionnalités principales

- Authentification sécurisée (JWT)
- Interface utilisateur fluide et moderne (React)
- API REST avec documentation interactive (Swagger)
- Gestion des étudiants, cours, absences, résultats et problèmes signalés

---

## 📸 Interface utilisateur (Aperçu)

Voici la page de connexion pour les étudiants :

<img width="330" src="https://user-images.githubusercontent.com/112178680/230625713-969b0e34-feac-4352-a0bc-b62efd27e8d1.png" alt="MIT LicenSe">

> Interface épurée avec navigation latérale, options sociales, et design réactif.

---

## 🗄️ Schéma de base de données (EER Diagram)

Modèle relationnel (MySQL Workbench) :

<img width="330" src="https://user-images.githubusercontent.com/112178680/230625741-558cf5e3-44f9-4549-ac7b-3c69cad67bcd.png" alt="MIT LicenSe">

> Tables : `student`, `studentcourses`, `studentresults`, `studentleaves`, `studentattendance`, `studentissues`

---

## 🔍 API REST – Documentation Swagger (FastAPI)

Documentation automatique générée par FastAPI :

<img width="330" src="https://user-images.githubusercontent.com/112178680/230625723-cb62ee16-4072-4225-a877-6407ce821e32.png" alt="MIT LicenSe">

> Endpoints pour connexion, gestion des étudiants, présence, résultats, etc.

---

## 🧱 Stack technique

| Frontend       | Backend      | Base de données | Outils                |
|----------------|--------------|------------------|------------------------|
| ReactJS        | FastAPI      | MySQL            | Swagger, Axios, JWT    |
| HTML/CSS/JS    | Pydantic     | SQLAlchemy ORM   | dotenv, Uvicorn       |

---

## ⚙️ Installation

### 📌 Prérequis

- Python 3.9+
- Node.js 16+
- MySQL (ou XAMPP/WAMP)
- (Optionnel) Docker

### 🔧 Backend (FastAPI)

```bash
cd backend
python -m venv venv
venv\Scripts\activate      # ou source venv/bin/activate sous Linux/Mac
pip install -r requirements.txt
uvicorn main:app --reload
cd frontend
npm install
npm start
CREATE DATABASE school_db;
-- puis importer le script school_db.sql si disponible
SchoolWebApp/
├── backend/
│   └── ...
├── frontend/
│   └── ...
├── screenshots/
│   ├── studentsignin.png
│   ├── eer_diagram.png
│   └── fastapi_docs.png
└── README.md

---

### 🎯 Prochaine étape

Assure-toi de :
- Placer les images renommées dans `screenshots/` :
  - `studentsignin.png`
  - `eer_diagram.png`
  - `fastapi_docs.png`
- Commiter le tout dans ton dépôt GitHub.

Souhaites-tu que je te crée une archive `.zip` avec tout prêt à l’emploi ?

