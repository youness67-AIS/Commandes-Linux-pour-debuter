# Commandes-Linux-pour-débuter
# 🐧 Mémo des Commandes Linux (Essentiel)

Ce guide regroupe les commandes indispensables pour débuter sereinement sur Linux sans se perdre dans les détails.

---

### 📂 Navigation & Emplacement
| Commande | Action |
| :--- | :--- |
| `ls` | Lister le contenu du dossier |
| `ls -la` | Lister tout (même les fichiers cachés) |
| `cd <nom>` | Entrer dans un dossier |
| `cd ..` | Revenir au dossier précédent |
| `pwd` | Afficher le chemin actuel |

---

### 📝 Gestion des Fichiers
* **Créer :** `touch fichier.txt` (fichier) ou `mkdir dossier` (dossier).
* **Renommer/Déplacer :** `mv ancien_nom nouveau_nom`.
* **Copier :** `cp source destination`.
* **Supprimer :** `rm fichier` ou `rm -r dossier` (suppression récursive).

---

### 🔍 Lecture & Recherche
* `cat <fichier>` : Afficher le contenu complet.
* `head -n 5 <fichier>` : Voir les 5 premières lignes.
* `grep "texte" <fichier>` : Chercher un mot dans un fichier.
* `find . -name "*.py"` : Trouver tous les fichiers Python ici.

---

### ⚡ Système & Administration
* `sudo <commande>` : Exécuter en tant qu'administrateur (root).
* `chmod +x <script.sh>` : Rendre un script exécutable.
* `clear` : Nettoyer le terminal.
* `top` : Voir l'utilisation du processeur et de la RAM en direct.

---

### ⌨️ Raccourcis de survie
- **Tabulation :** Auto-complétion (écrit la fin du mot pour vous).
- **Flèche Haut :** Rappeler la dernière commande.
- **Ctrl + C :** Annuler la commande en cours.
- **Ctrl + D :** Fermer le terminal.
