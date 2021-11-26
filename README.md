# eval1 : Ferme urbaine de la Ville Oger

La ville Oger est une ferme urbaine située dans un quartier de Saint-Brieuc.
Leur site internet était tellement vieux qu'il leur fallait un nouveau site moderne et surtout 'mobile first'. Et oui, même une ferme a besoin d'être visible, et la nouvelle direction en est bien consciente.

## Le choix des technologies

Le critère 'mobile first' m'oriente directement vers le framework Bootstrap.
Après avoir suivi les cours de Studi, et en complément le cours Bootstrap de Pierre Giraud, je décide de créer mon fichier index.html et de lui ajouter les liens vers le CDN Bootstrap 4.6.1 :

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css"
  integrity="sha384-zCbKRCUGaJDkqS1kPbPd7TveP5iyJE0EjAuZQTgFLD2ylzuqKfdKlfG/eSrtxUkn"
  crossorigin="anonymous"
/>
<script
  src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js"
  integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
  crossorigin="anonymous"
></script>
<script
  src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/js/bootstrap.bundle.min.js"
  integrity="sha384-fQybjgWLrvvRgtW6bFlB7jaZrFsaBXjsOMm/tB9LTS58ONXgqbR9W8oWht/amnpF"
  crossorigin="anonymous"
></script>
```

## Design singulier

Après un échange avec le directeur de la ferme. Sa demande se précise, il souhaite un site qui ressemble à sa ferme/base de loisirs: mettre en avant le coté nature.
Pour répondre à cette demande, je décide de créer un fichier styles.css afin de pallier au formalisme de Bootstrap. L'objectif premier est de rajouter une photo de la ferme en background :

```css
body {
  background-image: url("images/background1.JPG");
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: fixed;
}
```

Ce fichier a pour but à terme de reprendre la main en css si les outils Bootstrap ne répondent pas à mes attentes.

## Organisation du répertoire eval1

Afin de faire une première proposition, j ai besoin de 2 pages, il me faut donc créer un fichier event.html et un sous-dossier images/ afin d'y placer toutes mes photos.
Petit récapitulatif du répertoire à ce stade :

- index.html
- event.html
- style.css
- images/

## Dépot sur Github

Création du repository sur Github incluant la création d'un fichier README.md dont voici le lien :
https://github.com/erekhose35/eval1
Le premier commit "Initial commit" est créer à cette occasion

## Ressources utilisées pour la réalisation de ce site

Concernant la réalisation du site :

- Les cours Studi sur html/css et Bootstrap
- Les cours de Pierre Giraud sur Bootstrap
- La documentation Bootstrap

Concernant la mise en dépot Github

- Les cours Studi Git/Github
- Les cours Grafikart sur Git
