# Ajout des photos — guide complet

## Ce qu'il y a à faire (résumé)

1. Mettre à jour le site avec les 2 nouveaux fichiers (`index.html` + `photos.js`)
2. Installer GitHub Desktop et récupérer le dépôt
3. Déposer les 28 dossiers de photos au bon endroit
4. Envoyer (commit + push) — le site se met à jour tout seul

---

## Étape 1 — Mettre à jour le site (2 minutes)

1. Téléchargez les deux nouveaux fichiers : `index.html` et `photos.js`
2. Ouvrez https://github.com/smondain/stephanmondain.com
3. **Add file → Upload files** → glissez `index.html` et `photos.js`
   (GitHub proposera de remplacer l'ancien `index.html` : c'est normal, acceptez)
4. **Commit changes**

## Étape 2 — Installer GitHub Desktop (5 minutes)

1. Allez sur https://desktop.github.com et cliquez **Télécharger pour Windows** (ou Mac)
2. Installez et ouvrez l'application
3. **File → Options → Comptes** : connectez-vous avec votre compte GitHub (smondain)
4. **File → Clone repository** → choisissez `smondain/stephanmondain.com` → **Clone**

## Étape 3 — Déposer les photos (le gros du travail)

1. Dans GitHub Desktop : bouton **Repository → Show in Explorer** (ou « Afficher dans l'Explorateur ») — le dossier du site s'ouvre
2. Dans ce dossier, créez un dossier `images`, et dedans un dossier `portraits`
3. Résultat attendu : `stephanmondain.com/images/portraits/`
4. Dans Google Drive, ouvrez le dossier **Portraits** : téléchargez chaque sous-dossier (clic droit sur le dossier → **Télécharger**). Drive en fait un fichier ZIP
5. Décompressez chaque ZIP (clic droit → **Extraire tout**)
6. Renommez les dossiers extraits en minuscules sans accents et avec des tirets, puis glissez-les dans `images/portraits/` :

**Noms de dossiers exacts à respecter** (28) :
`aurore` · `blaine` · `camille` · `cassandra` · `charline` · `dorothee` · `emmanuelle` · `eugenie` · `henri` · `herminie` · `ilynca` · `jade` · `jean-charles` · `juliette` · `justine` · `kareen` · `lila` · `lisa` · `lise` · `maeva` · `margot` · `marie` · `marie-laurence` · `michele` · `paola` · `pauline` · `richard` · `tina`

⚠️ **Important** : ne renommez pas les photos elles-mêmes — le site les reconnaît par leur nom de fichier exact (ex. « 2023 05 Jade 119-Site.jpg »). Seuls les noms de dossiers ci-dessus comptent.

7. À la fin, `images/portraits/` doit contenir 28 dossiers, et chaque dossier doit contenir les photos (pas un sous-dossier supplémentaire)

## Étape 4 — Envoyer (2 minutes)

1. Revenez dans GitHub Desktop : il affiche la liste des fichiers ajoutés
2. En bas à gauche, tapez un titre : « photos portraits »
3. Cliquez **Commit to main**, puis **Push origin**
4. Attendez l'upload (quelques minutes selon votre connexion — ~400 Mo)

C'est terminé ! Ouvrez votre site `*.workers.dev` : la page **Portraits** affiche vos 28 galeries, et chaque galerie montre vos vraies photos, avec navigation plein écran (flèches ← → au clavier) et protections anti-téléchargement.

---

## Astuce anti-erreur

Si après l'upload une galerie affiche des cases vides : le nom du dossier ne correspond pas (majuscule, accent, espace). Vérifiez-le par rapport à la liste ci-dessus. Les photos manquantes s'affichent en images vides, jamais en erreur bloquante.

## Et pour la suite ?

Quand vous déposerez les galeries **Modèles**, **Paysages** et **Autres** dans Drive (mêmes règles), je générerai la suite du plan de chargement (`photos.js` mis à jour) et ces sections s'activeront à leur tour.
