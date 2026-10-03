# Duality — version finale

## 1. GitHub Pages (public)

Mettre à la racine du dépôt :

```text
index.html
admin.html
config.js
.nojekyll
assets/
  duality-header.jpg
  duality-cover.jpg
  duality-book-showcase.jpg
```

Ne pas publier `Code.gs` ni `AdminApp.html` sur GitHub Pages.

## 2. Google Apps Script

Dans le même projet Apps Script :

- remplace `Code.gs` par le nouveau `Code.gs`
- ajoute un fichier HTML nommé exactement `AdminApp`
- colle dedans `AdminApp.html`

Le Spreadsheet ID est déjà configuré :
`1xJiaC4j6oP-csoAIPTcdHRt_2vPcVvxZzddzGjRUkF0`

## 3. Déploiement Apps Script

Déploie le projet en **Application Web** :

- Exécuter en tant que : **toi**
- Qui a accès : **Toute personne disposant du lien**

Puis crée une nouvelle version du déploiement.

L'URL `/exec` déjà fournie est conservée dans `config.js`.

## 4. Admin

URL GitHub Pages :

`https://northvale-studio.github.io/duality-quiz-clans/admin.html`

Cette page ouvre le dashboard servi côté Google Apps Script.

Identifiant :
`admin`

Mot de passe :
`Yasmine_results!*`

## 5. Ce que l'admin affiche

Pour TOUS les participants :
- date/heure
- prénom
- nom
- e-mail
- clan
- score Lumières
- score Ombres
- oui/non pour invitations et actualités
- détail des 13 réponses

La récupération des données ne dépend pas de la case d'inscription : une participation est enregistrée même sans e-mail et même sans consentement aux événements.

## 6. Exports

Les boutons d'export exportent TOUJOURS la totalité des participants présents dans le Sheet.

Excel :
- toutes les personnes
- consentement oui/non
- clan
- scores
- les 13 réponses dans des colonnes séparées

PDF :
- toutes les personnes
- consentement
- clan
- scores
- réponses détaillées

Les filtres du tableau ne changent pas la base exportée.

## 7. Partie livre

La partie livre et les trois destinations restent :

Amazon :
https://www.amazon.fr/Duality-1-Yasmine-Houb/dp/2810620326

Fnac :
https://www.fnac.com/a21951564/Yasmine-Houb-Duality

Google Play :
https://play.google.com/store/books/details?id=v6J3EQAAQBAJ&rdid=book-v6J3EQAAQBAJ&rdot=1&source=gbs_atb&pcampaignid=books_booksearch_atb
