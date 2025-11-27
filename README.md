# Woody.fr
# Déployer un site Canva sur GitHub Pages


1. Ouvre ce dépôt localement ou crée un nouveau dépôt sur GitHub.
2. Remplace le contenu de `index.html` par le HTML exporté depuis Canva (ouvre le fichier exporté et copie tout).
3. Commit & push sur la branche `main`.
4. Dans GitHub : Paramètres → Pages → Source : `main` branch (root) → Enregistrer.
5. Attends quelques minutes — ton site sera disponible à `https://<ton-username>.github.io/<repo>`.


Alternatives : tu peux aussi déployer sur Netlify ou Vercel (drag & drop ou connexion au repo).


Notes :
- Si ton export Canva utilise des chemins relatifs vers des fichiers CSS/JS/images, assure-toi d'ajouter ces fichiers au même emplacement dans le repo.
- Pour Google AdSense : colle le script AdSense dans le <head> ou aux emplacements d'annonce, après t'être assuré d'avoir un compte approuvé.
