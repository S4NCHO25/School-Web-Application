# 🎓 SchoolWebApp

Une application web de gestion scolaire complète, développée avec **ReactJS** pour le frontend, **FastAPI** pour le backend, et **MySQL** comme base de données.

---

## 🚀 Fonctionnalités principales

- Gestion des utilisateurs (étudiants, enseignants, administrateurs)
- Authentification avec JWT
- Gestion des absences, résultats, cours et réclamations
- Interface utilisateur moderne et responsive (ReactJS)
- API REST avec documentation interactive (FastAPI + Swagger)
- Stockage relationnel (MySQL)

---

## 📸 Interface utilisateur (Aperçu)

Voici la page de connexion pour les étudiants :

<img width="330" src="https://user-images.githubusercontent.com/112178680/230625713-969b0e34-feac-4352-a0bc-b62efd27e8d1.png" alt="MIT LicenSe">

> Interface épurée avec navigation latérale, options sociales, et design réactif.

---

## 🗄️ Schéma de base de données (EER Diagram)

Modèle de données relationnel (MySQL Workbench) :

<img width="330" src="https://user-images.githubusercontent.com/112178680/230625723-cb62ee16-4072-4225-a877-6407ce821e32.png" alt="MIT LicenSe">

> Tables : `student`, `studentcourses`, `studentresults`, `studentleaves`, `studentattendance`, `studentissues`

---

## 🧱 Technologies utilisées

| Frontend       | Backend      | Base de données | Autres              |
|----------------|--------------|------------------|----------------------|
| ReactJS        | FastAPI      | MySQL            | JWT Auth, Axios      |
| HTML/CSS/JS    | Pydantic     | SQLAlchemy        | dotenv, Alembic     |

---

## ⚙️ Installation

### 📌 Prérequis

- Python 3.9+
- Node.js 16+
- MySQL Server (ou XAMPP/WAMP)
- (Optionnel) Docker

---

### 🔧 Backend (FastAPI)

```bash
cd backend
python -m venv venv
venv\Scripts\activate        # Linux/macOS: source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload
cd frontend
npm install
npm start
CREATE DATABASE school_db;
-- puis importer le fichier school_db.sql via phpMyAdmin ou terminal
SchoolWebApp/
├── backend/
│   ├── main.py
│   └── ...
├── frontend/
│   └── src/
├── school_db.sql
├── screenshots/
│   ├── studentsignin.png
│   └── eer_diagram.png
└── README.md

---

### 📁 À faire :

- Place les **images** renommées dans un dossier `screenshots/` à la racine du projet :
  - `screenshots/studentsignin.png` → image de login
  - `screenshots/eer_diagram.png` → image EER MySQL

Souhaite-tu que je te donne directement le fichier `README.md` prêt à télécharger ?
