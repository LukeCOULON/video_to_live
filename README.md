# LiveFrame

LiveFrame est un petit site **HTML / CSS / JavaScript** qui permet de transformer une vidéo en une image clé et une courte séquence vidéo, directement dans le navigateur.

Aucun serveur ni installation complexe n'est nécessaire.

## ✨ Fonctionnalités

- Importer une vidéo depuis son appareil
- Prévisualiser la vidéo
- Choisir le début de la séquence
- Choisir sa durée
- Choisir l'image principale
- Exporter l'image en `.jpg`
- Exporter la séquence vidéo
- Fonctionne directement dans le navigateur
- Les fichiers restent localement sur l'appareil

## 🚀 Utilisation

### 1. Télécharger le projet

Clone le dépôt GitHub ou télécharge le projet en ZIP.

```bash
git clone https://github.com/TON-USERNAME/liveframe.git
cd liveframe
```

### 2. Ouvrir le site

Le projet ne nécessite pas de framework ni de dépendance.

Tu peux simplement ouvrir :

```text
index.html
```

dans ton navigateur.

Tu peux aussi utiliser un petit serveur local, par exemple avec VS Code et l'extension **Live Server**.

### 3. Importer une vidéo

Clique sur **« Importer une vidéo »** et sélectionne une vidéo depuis ton ordinateur ou ton téléphone.

Les formats vidéo supportés dépendent du navigateur utilisé.

### 4. Choisir le passage

Après avoir importé la vidéo :

- indique le **début** de la séquence ;
- indique sa **durée** ;
- déplace le curseur pour choisir l'**image principale**.

Une durée comprise entre environ **1,5 et 3 secondes** est recommandée.

### 5. Exporter

Clique sur :

**« Créer les fichiers Live Photo »**

Le navigateur va générer :

```text
live-photo-keyframe.jpg
live-photo-video.mp4
```

ou, selon les capacités du navigateur :

```text
live-photo-keyframe.jpg
live-photo-video.webm
```

Les fichiers sont téléchargés directement sur ton appareil.

## 📱 Important pour iPhone

Une Live Photo Apple n'est pas simplement composée d'une photo et d'une vidéo.

iOS utilise notamment des métadonnées et une association spécifique entre les deux fichiers.

Cette version de LiveFrame prépare donc les éléments nécessaires, mais **l'export actuel ne garantit pas que les fichiers seront automatiquement reconnus comme une vraie Live Photo par l'application Photos d'iPhone**.

Pour obtenir une vraie Live Photo compatible avec Photos, il faut ensuite utiliser un outil capable d'associer correctement la photo et la vidéo avec les métadonnées Live Photo d'Apple.

## 🔒 Confidentialité

LiveFrame fonctionne côté navigateur.

La vidéo sélectionnée n'est pas envoyée automatiquement vers un serveur.

Le traitement est effectué localement sur l'appareil.

## 🛠️ Technologies

Le projet utilise uniquement :

- HTML
- CSS
- JavaScript
- API vidéo du navigateur
- Canvas
- MediaRecorder

Aucune dépendance npm n'est nécessaire.

## 📁 Structure

```text
liveframe/
└── index.html
```

Tout le site se trouve actuellement dans un seul fichier.

## 🌐 GitHub Pages

Le projet peut être publié gratuitement avec **GitHub Pages**.

Après avoir envoyé `index.html` sur GitHub :

1. Va dans **Settings** du dépôt.
2. Ouvre **Pages**.
3. Sélectionne la branche contenant le projet.
4. Choisis le dossier `/root`.
5. Enregistre.

GitHub générera ensuite une adresse permettant d'ouvrir LiveFrame directement dans le navigateur.

## 📄 Licence

Tu peux ajouter la licence de ton choix selon l'utilisation prévue du projet.
