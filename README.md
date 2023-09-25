Challenge S04E01 - Pratique HTML
## Exercice 1: Création de base d'une page HTML
**Objectif** : Familiarisez-vous avec la structure de base d'un document HTML.
**Instructions** :
1. Créez un nouveau fichier nommé "index.html".
1. À l'intérieur, établissez la structure de base d'un document HTML avec les éléments `<!DOCTYPE>`, `<html>`, `<head>`, et `<body>`.

**Résultat attendu** : Une page HTML vide avec la structure de base.

### Corrigé Exercice 1: Création de base d'une page HTML
```
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document de base</title>
</head>
<body>
    <!-- Votre contenu ira ici à l'avenir -->
</body>
</html>
```

## Exercice 2: Listes, liens et images
**Objectif** : Comprendre et pratiquer l'intégration de listes, liens et images dans une page HTML.
**Instructions** :
1. À l'intérieur de votre fichier "index.html", ajoutez une liste à puces contenant trois éléments: "Accueil", "À propos", "Contact".
1. Transformez chaque élément de la liste en lien. Faites en sorte que le lien "Contact" dirige vers une adresse e-mail (par exemple : `mailto:contact@exemple.fr`).
1. Sous la liste, insérez une image de votre choix (vous pouvez utiliser des plateformes comme Unsplash pour obtenir des images gratuites). Assurez-vous d'ajouter un attribut "alt" pour décrire l'image.
**Résultat attendu** : Une page contenant une liste à puces avec des liens et une image.
### Corrigé Exercice 2: Listes, liens et images
```
<!DOCTYPE html>
<html lang="fr">
<head>
    <!-- ... autres éléments du <head> ... -->
    <title>Listes, liens et images</title>
</head>
<body>
    <ul>
        <li><a href="#">Accueil</a></li>
        <li><a href="#">À propos</a></li>
        <li><a href="mailto:contact@exemple.fr">Contact</a></li>
    </ul>

    <img src="chemin_vers_votre_image.jpg" alt="Description de l'image">
</body>
</html>
```
## Exercice 3: Formulaires et entrées
**Objectif** : Créer un formulaire simple pour recueillir des informations de contact.
**Instructions** :
1. Créez un formulaire avec les champs suivants :
1. Ajoutez un bouton "Envoyer" pour soumettre le formulaire.
1. Pour l'instant, le formulaire n'a pas besoin d'être fonctionnel. Vous pouvez ajouter l'attribut `action="#"` à l'élément `<form>` pour qu'il ne fasse rien lors de la soumission.
**Résultat attendu** : Une page avec un formulaire contenant trois champs et un bouton de soumission.
### Corrigé Exercice 3: Formulaires et entrées
```
<!DOCTYPE html>
<html lang="fr">
<head>
    <!-- ... autres éléments du <head> ... -->
    <title>Formulaires et entrées</title>
</head>
<body>
    <form action="#">
        <label for="nom">Nom :</label>
        <input type="text" id="nom" name="nom">
        
        <label for="email">Adresse e-mail :</label>
        <input type="email" id="email" name="email">

        <label for="message">Message :</label>
        <textarea id="message" name="message"></textarea>

        <input type="submit" value="Envoyer">
    </form>
</body>
</html>
```
## Exercice 4: Intégration de médias
**Objectif** : Intégrer une vidéo et un fichier audio sur votre page.
**Instructions** :
1. Trouvez une vidéo de démonstration (par exemple, sur des sites comme Pexels ou Pixabay) et téléchargez-la.
1. Intégrez cette vidéo à votre page en utilisant la balise `<video>`. Assurez-vous d'ajouter des contrôles pour que les utilisateurs puissent lire, mettre en pause et ajuster le volume de la vidéo.
1. De même, trouvez un fichier audio (par exemple, sur FreeSound ou d'autres ressources libres) et intégrez-le à votre page en utilisant la balise `<audio>`, avec des contrôles similaires.
**Résultat attendu** : Une page avec une vidéo et un fichier audio intégrés, chacun ayant des contrôles pour l'utilisateur.
### Corrigé Exercice 4: Intégration de médias
```
<!DOCTYPE html>
<html lang="fr">
<head>
    <!-- ... autres éléments du <head> ... -->
    <title>Intégration de médias</title>
</head>
<body>
    <video controls>
        <source src="chemin_vers_votre_video.mp4" type="video/mp4">
        Votre navigateur ne supporte pas la balise vidéo.
    </video>

    <audio controls>
        <source src="chemin_vers_votre_audio.mp3" type="audio/mpeg">
        Votre navigateur ne supporte pas la balise audio.
    </audio>
</body>
</html>
```