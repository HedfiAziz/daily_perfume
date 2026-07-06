# 🌟 Daily Perfume - Maison de Haute Parfumerie

Une application web vitrine élégante et luxueuse développée avec **Python (Flask)** pour une maison de parfum basée en Tunisie. Ce projet met en valeur des collections exclusives de parfums, muscs, et fragrances d'ambiance à travers une interface utilisateur premium et épurée.

## ✨ Fonctionnalités

* **Design UI/UX Premium :** Une charte graphique luxueuse (Noir, Blanc, Or) avec des animations fluides.
* **Catalogue Dynamique :** Présentation des produits divisée en 4 grandes collections :
    * Parfums (Hommes, Femmes, Unisexe)
    * Muscs Précieux
    * Parfums d'Ambiance
    * Parfums de Voiture
* **Pages Produits Détaillées :** Génération dynamique des pages produits via les routes Flask (`/product/<id>`).
* **Formulaire de Contact Actif :** Intégration SMTP permettant l'envoi d'e-mails directement depuis le site vers l'adresse de la boutique.
* **Responsive Design :** Interface 100% adaptée aux smartphones, tablettes et écrans larges.

## 🛠️ Technologies Utilisées

* **Backend :** Python, Flask
* **Frontend :** HTML5, CSS3 (Custom CSS, sans framework lourd)
* **Typographie :** Google Fonts (Montserrat & Playfair Display)

## 📁 Structure du Projet

```text
daily-perfume/
│
├── app.py                  # Fichier principal (Cerveau de l'application Flask)
├── requirements.txt        # Dépendances du projet
│
├── static/                 # Fichiers statiques (Images, CSS)
│   ├── css/
│   │   └── style.css       # Styles principaux
│   └── images/             # Images des produits et bannières
│
└── templates/              # Templates HTML (Jinja2)
    ├── base.html           # Squelette principal du site (Header, Footer)
    ├── index.html          # Page d'accueil et catalogue
    ├── product.html        # Page de détails d'un produit
    └── contact.html        # Page de contact
