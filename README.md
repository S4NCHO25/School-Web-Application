# 🎓 SchoolWebApp

Une application web de gestion scolaire complète, développée avec **ReactJS** pour le frontend, **FastAPI** pour le backend, et **MySQL** comme base de données.

---

## 🚀 Fonctionnalités principales

- Gestion des utilisateurs (étudiants, enseignants, administrateurs)
- Authentification et autorisation JWT
- Création et gestion des cours
- Suivi des notes et évaluations
- Interface réactive et moderne (ReactJS)
- API REST performante (FastAPI)
- Base de données relationnelle (MySQL)

---

## 🧱 Technologies utilisées

| Frontend       | Backend      | Base de données | Autres              |
|----------------|--------------|------------------|----------------------|
| ReactJS        | FastAPI      | MySQL            | Axios, React Router |
| HTML/CSS/JS    | Pydantic     | SQLAlchemy        | JWT Auth, CORS      |
| Bootstrap/Tailwind (optionnel) | Uvicorn       |                     | dotenv, Alembic     |

---

## 🛠️ Installation et exécution

### 📌 Prérequis

- Python 3.9+
- Node.js 16+
- MySQL Server (ou XAMPP/WAMP)
- (Optionnel) Docker

---

### ⚙️ Backend (FastAPI)

```bash
cd backend
python -m venv venv
venv\Scripts\activate        # Linux/macOS: source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload
