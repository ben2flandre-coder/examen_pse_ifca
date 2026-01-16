# 🚀 Guide de Déploiement GitHub Pages - Version 2.0

## Guide complet pour publier le questionnaire PSE IFCA/PAC v2

---

## 📋 Prérequis

- Un compte GitHub (gratuit) : https://github.com/signup
- Les fichiers du package téléchargés sur votre ordinateur

---

## 🗂️ Fichiers à Uploader (10 fichiers)

### Fichiers Essentiels
✅ `examen_PSE_IFCA_PAC_v2.html` (123 Ko) - **PRINCIPAL (logos intégrés en base64)**
✅ `index.html` (2 Ko) - Redirection automatique vers V2

### Fichiers PNG (optionnels)
⚪ `logo_greta.png` (7 Ko) - Optionnel (déjà intégré en base64 dans le HTML)
⚪ `logo_forpro.png` (25 Ko) - Optionnel (déjà intégré en base64 dans le HTML)

### Documentation
✅ `README.md` - Documentation du projet
✅ `DEPLOYMENT_GUIDE.md` - Ce fichier
✅ `CHECKLIST.md` - Liste de vérification
✅ `LICENSE.md` - Conditions d'utilisation
✅ `.gitignore` - Configuration Git

### Archive (optionnel)
⚪ `examen_PSE_IFCA_PAC.html` (46 Ko) - Version 1.0 (ancienne version)

**💡 Note importante** : Les logos sont maintenant encodés en base64 directement dans le fichier HTML. Les fichiers PNG ne sont plus nécessaires pour le fonctionnement mais peuvent être conservés dans le dépôt pour référence.

---

## 🔧 Étape 1 : Créer un Dépôt GitHub

1. **Connectez-vous à GitHub** : https://github.com/login

2. **Créez un nouveau dépôt** :
   - Cliquez sur le bouton **"New"** (vert) ou le **"+"** en haut à droite → "New repository"
   
3. **Configurez le dépôt** :
   - **Repository name** : `examen-pse-ifca-pac` (ou autre nom sans espaces)
   - **Description** : "Questionnaire PSE IFCA/PAC v2.0 - GRETA du Var - Formations professionnelles"
   - **Visibilité** : 
     - ✅ **Public** (recommandé - GitHub Pages gratuit)
     - ⚠️ Private (nécessite GitHub Pro pour Pages)
   - **Initialize** :
     - ✅ Cochez "Add a README file"
   
4. **Créez le dépôt** :
   - Cliquez sur **"Create repository"**

---

## 📤 Étape 2 : Uploader les Fichiers

### Méthode Simple (Interface Web)

1. **Dans votre nouveau dépôt**, cliquez sur **"Add file"** → **"Upload files"**

2. **Glissez-déposez** ou sélectionnez les 10 fichiers listés ci-dessus

3. **Important** : 
   - Les logos DOIVENT être nommés exactement `logo_greta.png` et `logo_forpro.png`
   - Le fichier principal DOIT être `examen_PSE_IFCA_PAC_v2.html`
   - Tous les fichiers doivent être **à la racine** du dépôt (pas dans un sous-dossier)

4. **Message de commit** :
   - Exemple : "Ajout questionnaire PSE IFCA/PAC v2.0 avec signature numérique"

5. **Cliquez sur** "Commit changes"

---

## 🌐 Étape 3 : Activer GitHub Pages

1. **Dans votre dépôt**, cliquez sur **"Settings"** (⚙️ en haut à droite)

2. **Menu latéral gauche**, descendez et cliquez sur **"Pages"**

3. **Configurez la source** :
   - **Source** : Sélectionnez "Deploy from a branch"
   - **Branch** : Sélectionnez `main` (ou `master` selon votre config)
   - **Folder** : Sélectionnez `/ (root)`
   
4. **Cliquez sur "Save"**

5. **Attendez le déploiement** :
   - ⏱️ Environ 2-3 minutes
   - Un message apparaîtra : "Your site is live at https://[username].github.io/[repo]/"
   - 🟢 Le lien devient cliquable une fois le déploiement terminé

---

## ✅ Étape 4 : Vérifier le Déploiement

### URLs à tester

1. **Page d'accueil** (redirection automatique) :
```
https://[VOTRE-USERNAME].github.io/examen-pse-ifca-pac/
```

2. **Questionnaire V2 direct** :
```
https://[VOTRE-USERNAME].github.io/examen-pse-ifca-pac/examen_PSE_IFCA_PAC_v2.html
```

3. **Questionnaire V1** (si uploadé) :
```
https://[VOTRE-USERNAME].github.io/examen-pse-ifca-pac/examen_PSE_IFCA_PAC.html
```

### Checklist de vérification

- [ ] La page s'affiche correctement
- [ ] Les **deux logos** apparaissent en bannière
- [ ] Le **cartouche d'identification** est visible
- [ ] Les champs du cartouche sont **éditables**
- [ ] Les **zones de réponse** sont éditables
- [ ] Les **cases à cocher** fonctionnent
- [ ] La **zone de signature** fonctionne (testez avec souris/doigt)
- [ ] Le bouton **"Effacer"** de la signature fonctionne
- [ ] Le bouton **"Envoyer par email"** ouvre le client mail
- [ ] L'**adresse email** est bien `benoit.deflandre@ac-nice.fr`
- [ ] Le document s'**imprime correctement** (Ctrl+P)
- [ ] Sur **mobile/tablette** : la signature au doigt fonctionne

---

## 🔄 Étape 5 : Personnaliser le README

1. **Ouvrez** `README.md` dans votre dépôt

2. **Cliquez** sur l'icône ✏️ "Edit this file"

3. **Remplacez** :
   - `[username]` par votre nom d'utilisateur GitHub
   - `[repo]` par le nom exact de votre dépôt

4. **Cliquez** "Commit changes"

---

## 📱 Partage aux Stagiaires

### Option 1 : Lien Direct
Envoyez l'URL par email / SMS / messagerie :
```
https://[votre-username].github.io/examen-pse-ifca-pac/
```

### Option 2 : QR Code
1. Aller sur https://www.qr-code-generator.com
2. Entrer votre URL
3. Télécharger le QR Code
4. Imprimer sur la convocation d'examen

### Option 3 : Lien Court
1. Aller sur https://bitly.com (gratuit)
2. Entrer votre URL longue
3. Créer un lien court : `bit.ly/pse-ifca-exam`
4. Plus facile à communiquer

---

## 🛠️ Dépannage

### Problème : Le site ne s'affiche pas après 10 minutes

**Solutions** :
1. Vérifier : Settings → Pages → GitHub Pages est bien activé
2. Vérifier : La branch sélectionnée est `main` (ou `master`)
3. Vérifier : Folder est bien `/ (root)`
4. Aller dans : Actions → voir si le déploiement a échoué
5. Forcer le redéploiement : modifier un fichier et commit

### Problème : Les logos ne s'affichent pas

**Normalement, ce problème ne devrait plus arriver** car les logos sont maintenant intégrés en base64 dans le HTML.

Si malgré tout les logos n'apparaissent pas :
1. Vider le cache du navigateur (Ctrl+Shift+R ou Cmd+Shift+R)
2. Vérifier que vous utilisez bien `examen_PSE_IFCA_PAC_v2.html` (123 Ko)
3. Vérifier qu'il n'y a pas d'erreur dans la console du navigateur (F12)

**Note** : Les fichiers PNG `logo_greta.png` et `logo_forpro.png` ne sont plus utilisés directement par le questionnaire.

### Problème : La signature ne fonctionne pas

**Sur ordinateur** :
- Tester avec la souris en maintenant le clic
- Vérifier que JavaScript est activé

**Sur mobile** :
- Utiliser le doigt directement sur la zone
- Désactiver le zoom automatique du navigateur
- Tester en mode "Bureau" du navigateur si problème

### Problème : L'envoi email ne fonctionne pas

**Causes** :
- Pas de client mail configuré (Outlook, Thunderbird, Mail)
- Le navigateur bloque les liens `mailto:`

**Solutions** :
1. Configurer un client mail sur l'ordinateur
2. Utiliser un webmail (Gmail, Outlook.com) :
   - Copier manuellement l'adresse : benoit.deflandre@ac-nice.fr
   - Copier les réponses depuis le formulaire
3. Utiliser la fonction "Imprimer en PDF" comme alternative

### Problème : Page blanche / Erreur 404

**Causes** :
- Le fichier `index.html` n'est pas à la racine
- Le fichier `examen_PSE_IFCA_PAC_v2.html` n'est pas à la racine
- Le déploiement n'est pas terminé

**Solutions** :
1. Vérifier que tous les fichiers sont bien à la racine (pas dans un dossier)
2. Attendre 5 minutes supplémentaires
3. Accéder directement au fichier : `/examen_PSE_IFCA_PAC_v2.html`

---

## 🔧 Mise à Jour du Questionnaire

### Pour modifier le contenu :

1. **Cliquez** sur `examen_PSE_IFCA_PAC_v2.html` dans votre dépôt

2. **Cliquez** sur l'icône ✏️ "Edit this file"

3. **Faites** vos modifications (HTML/CSS/JS)

4. **Cliquez** "Commit changes"

5. **Attendez** 1-2 minutes pour la mise à jour

### Pour remplacer complètement le fichier :

1. **Supprimez** l'ancien : cliquez sur le fichier → "⋮" → "Delete file"

2. **Uploadez** le nouveau : "Add file" → "Upload files"

3. **Même nom** : `examen_PSE_IFCA_PAC_v2.html`

---

## 📊 Suivi des Consultations

### Via GitHub Insights (limité)

1. Onglet **"Insights"** de votre dépôt
2. **"Traffic"** → voir visiteurs et vues
3. Données sur 14 jours glissants

### Via Google Analytics (optionnel)

1. Créer un compte : https://analytics.google.com
2. Créer une propriété
3. Copier le code de suivi
4. Ajouter dans `<head>` du fichier HTML
5. Commit et attendre mise à jour

---

## 🔐 Confidentialité

### Dépôt Public (défaut)
- ✅ GitHub Pages gratuit
- ⚠️ Tout le monde peut voir le code source
- 💡 OK si le contenu n'est pas confidentiel

### Dépôt Privé
- 💰 Nécessite GitHub Pro (4$/mois)
- 🔒 Seuls vous et vos collaborateurs voient le code
- 🌐 Le site reste accessible publiquement (Pages)

**Pour rendre privé** :
Settings → Danger Zone → Change repository visibility → Make private

---

## 📞 Support

### Ressources
- 📖 GitHub Pages : https://pages.github.com
- 📖 GitHub Docs : https://docs.github.com
- 💬 GitHub Community : https://github.community

### Contact Formateur
📧 benoit.deflandre@ac-nice.fr

---

## ✅ Checklist Finale

Avant de partager le lien :

- [ ] Site accessible en ligne
- [ ] Logos visibles en bannière
- [ ] Cartouche d'identification fonctionnel
- [ ] Zones de réponse éditables
- [ ] Cases à cocher fonctionnent
- [ ] Signature numérique fonctionne
- [ ] Bouton email ouvre le client mail
- [ ] Adresse email correcte
- [ ] Test sur mobile/tablette OK
- [ ] Test impression PDF OK
- [ ] QR Code créé (optionnel)
- [ ] Lien court créé (optionnel)
- [ ] Email de convocation préparé

---

## 🎉 Félicitations !

Votre questionnaire PSE IFCA/PAC v2.0 est maintenant en ligne !

**Points clés** :
- ✅ Accessible 24/7 depuis n'importe où
- ✅ Signature numérique tactile
- ✅ Contextes professionnels réalistes
- ✅ 100% gratuit avec GitHub Pages
- ✅ Facile à mettre à jour

---

**Bon déploiement ! 🚀**

**Date** : Janvier 2025 | **Version** : 2.0
