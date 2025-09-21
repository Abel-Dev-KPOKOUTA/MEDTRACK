# 🏥 MedTrack – Une plateforme innovante pour le suivi médical

![Statut](https://img.shields.io/badge/Statut-En%20cours%20de%20développement-yellow)
![Technologies](https://img.shields.io/badge/Technologies-Django%20|%20HTML%20|%20CSS%20|%20JS-blue)

## 📌 Présentation

**MedTrack** est une application web intelligente destinée à améliorer la communication entre **patients**, **médecins** et **assistants médicaux**.  
L’objectif est de fournir un **suivi personnalisé de la santé** des patients, en centralisant les informations médicales et en facilitant la prise en charge.

> ⚠️ **Statut du projet** : En cours de développement  
> ✅ L’interface patient est déjà opérationnelle (visualisation des symptômes, alertes, rendez-vous, messages).  
> 🛠️ L’interface médecin et celle des assistants sont en cours de finalisation.

---

## ✨ Fonctionnalités prévues

- 📊 **Tableau de bord patient** : suivi des symptômes, alertes, rendez-vous  
- 💬 **Messagerie temps réel** *(en développement)*  
- 🩺 **Téléconsultation intégrée** *(à venir)*  
- 📄 **Rapports médicaux PDF** générés automatiquement  
- 🔔 **Notifications intelligentes** pour un meilleur suivi  

---

## 🛠️ Technologies utilisées

- **Backend** : Django (Python)  
- **Frontend** : HTML, CSS, JavaScript  
- **Base de données** : PostgreSQL / SQLite (selon l’environnement)  
- **Outils** : Bootstrap, FontAwesome, GitHub pour la collaboration  

---

## 🚀 Installation et exécution (Développement)

```bash
# 1. Cloner le projet
git clone https://github.com/Abel-Dev-KPOKOUTA/MEDTRACK.git

cd MEDTRACK

# 2. Créer un environnement virtuel
python -m venv venv
source venv/bin/activate  # Sous Windows: venv\Scripts\activate

# 3. Installer les dépendances
pip install -r requirements.txt

# 4. Appliquer les migrations
python manage.py migrate

# 5. Lancer le serveur de développement
python manage.py runserver
