# ✅ Checklist de Déploiement Rapide - Version 2.0

## 📦 Fichiers Requis (10 fichiers)

Vérifiez que vous avez tous ces fichiers :

- [ ] `examen_PSE_IFCA_PAC_v2.html` (123 Ko) ⭐ **PRINCIPAL (logos intégrés)**
- [ ] `logo_greta.png` (7 Ko) - Optionnel (déjà intégré en base64)
- [ ] `logo_forpro.png` (25 Ko) - Optionnel (déjà intégré en base64)
- [ ] `index.html` (2 Ko)
- [ ] `README.md`
- [ ] `DEPLOYMENT_GUIDE.md`
- [ ] `CHECKLIST.md` (ce fichier)
- [ ] `LICENSE.md`
- [ ] `.gitignore`
- [ ] `examen_PSE_IFCA_PAC.html` (46 Ko) - Optionnel (v1)

**Note importante** : Les logos sont maintenant intégrés en base64 dans le fichier HTML principal. Les fichiers PNG peuvent être conservés dans le dépôt pour référence mais ne sont plus nécessaires au fonctionnement.

---

## 🚀 Déploiement en 5 Minutes

### 1️⃣ Créer le Dépôt GitHub (2 min)

- [ ] Aller sur https://github.com
- [ ] Cliquer "New repository" (bouton vert)
- [ ] **Nom** : `examen-pse-ifca-pac`
- [ ] **Visibilité** : Public ✅
- [ ] **Cocher** "Add a README file"
- [ ] Cliquer "Create repository"

### 2️⃣ Uploader les Fichiers (2 min)

- [ ] Cliquer "Add file" → "Upload files"
- [ ] **Glisser-déposer les 10 fichiers** (ou 9 sans v1)
- [ ] **Vérifier** : tous les fichiers à la **racine** (pas de dossier)
- [ ] Message : "Ajout questionnaire PSE v2.0"
- [ ] Cliquer "Commit changes"

### 3️⃣ Activer GitHub Pages (1 min)

- [ ] Cliquer "Settings" ⚙️
- [ ] Menu gauche → "Pages"
- [ ] **Source** : "Deploy from a branch"
- [ ] **Branch** : `main` / Folder : `/ (root)`
- [ ] Cliquer "Save"
- [ ] ⏱️ Attendre 2-3 minutes

### 4️⃣ Tester l'Accès

- [ ] Copier l'URL affichée : `https://[username].github.io/[repo]/`
- [ ] Ouvrir dans un navigateur
- [ ] Vérifier la redirection vers la v2

### 5️⃣ Vérifications Essentielles

- [ ] Les **2 logos** s'affichent en bannière ✨ (intégrés en base64)
- [ ] Le **cartouche** (Nom, Prénom, Groupe, Date) est visible
- [ ] Les **champs** sont éditables
- [ ] La **signature** fonctionne (testez avec souris/doigt)
- [ ] Les **boutons en haut** : 🖨️ Imprimer et 📄 PDF fonctionnent
- [ ] Le **bouton email** ouvre la modal avec options alternatives
- [ ] Test sur **mobile** : signature au doigt OK

---

## 🔗 URLs Finales

Notez vos URLs après déploiement :

**URL principale (redirection automatique) :**
```
https://[VOTRE-USERNAME].github.io/examen-pse-ifca-pac/
```

**URL directe questionnaire V2 :**
```
https://[VOTRE-USERNAME].github.io/examen-pse-ifca-pac/examen_PSE_IFCA_PAC_v2.html
```

---

## 📱 Partage aux Candidats

### Option 1 : Lien Direct
- [ ] Envoyer l'URL par email/SMS
- [ ] Inclure dans la convocation d'examen

### Option 2 : QR Code
- [ ] Générer sur https://www.qr-code-generator.com
- [ ] Télécharger l'image
- [ ] Imprimer sur convocations

### Option 3 : Lien Court
- [ ] Créer sur https://bitly.com
- [ ] Exemple : `bit.ly/pse-ifca-2025`
- [ ] Plus facile à communiquer

---

## ✅ Vérifications Avant Examen

### 24h avant
- [ ] Envoyer le lien aux candidats pour test d'accès
- [ ] Demander de tester la signature sur leur appareil
- [ ] Préparer alternatives papier (5-10% des candidats)

### Le jour J
- [ ] Vérifier que le site est accessible
- [ ] Tester la signature sur plusieurs appareils
- [ ] Rappeler aux candidats de remplir le cartouche
- [ ] Rappeler de signer avant l'envoi

### Après l'examen
- [ ] Vérifier réception de tous les emails
- [ ] Compiler dans un tableur
- [ ] Feedback individualisé

---

## 🛠️ Dépannage Express

| Problème | Solution Rapide |
|----------|-----------------|
| Site inaccessible | Vérifier Settings → Pages activé |
| Logos absents | Re-uploader à la racine, noms exacts |
| Signature ne marche pas | Tester clic maintenu (souris) ou doigt (mobile) |
| Email ne s'ouvre pas | Vérifier client mail configuré |
| Page blanche | Vérifier fichiers à la racine, attendre 5 min |

**Guide détaillé** : voir `DEPLOYMENT_GUIDE.md`

---

## 📞 Support

**Problème technique** : benoit.deflandre@ac-nice.fr  
**GitHub Docs** : https://docs.github.com/pages

---

## 🎯 Nouveautés V2 (Rappel)

✨ **Ce qui a changé par rapport à la v1** :
- ✅ Cartouche d'identification professionnel
- ✅ Signature numérique interactive (souris/doigt/stylet)
- ✅ Logos en bannière dédiée
- ✅ Contextes professionnels détaillés
- ✅ 22 questions (110 points) au lieu de 23 (100 points)
- ✅ Situations réelles de chantiers IFCA/PAC
- ✅ Cas pratique final enrichi (15 points)

---

## 📊 Statistiques Cibles

**Après déploiement, surveillez** :
- Nombre de consultations (GitHub Insights → Traffic)
- Taux de retour des emails
- Temps moyen de complétion
- Questions les plus difficiles

---

## ✅ Déploiement Terminé !

Une fois toutes les cases cochées, votre questionnaire est prêt !

**Prochaines étapes** :
1. ✉️ Envoyer convocations avec lien
2. 🔔 Rappel 24h avant avec test d'accès
3. 📱 Créer QR Code pour faciliter l'accès
4. 🖨️ Préparer copies papier de secours (5%)

---

**Bon courage pour les examens ! 🎓**

**Version** : 2.0 | **Date** : Janvier 2025
