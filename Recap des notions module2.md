# Intégration - Module 2

Récapitulatif des notions essentielles

## Boites
border
margin
padding
box-sizing : content-box / border-box

## Tableaux
table
tr
td
-> colsman
-> rowspan
th
-> colsman
-> rowspan
thead
tbody

## Flexbox
display: flex sur un container
(s'applique uniquement sur les enfants direct du container)
flex-direction: row (defaut) / column
flex-wrap: utilisé dans un contexte ou les enfants sortent du parent
justify-content :
-> si flex-direction row, alignement horizontal
-> si flex-direction column, alignement vertical
align-items
-> si flex-direction row, alignement vertical
-> si flex-direction column, alignement horizontal

## Images de fond
background-image: url()
background-size: cover /contain / 100% 100%
background-position: center center
background-repeat: repeat / no-repeat / repeat-x / repeat-y

## Formulaires
### Configuration
balise form
-> action : sur quelle URL sont envoyées les données
(par défaut sur la même URL qui affiche le formulaire. IL NE FAUT PAS OUBLIER DE METTRE UN / AU DEBUT DE CHAQUE URL!!!)
-> method : comment sont envoyées les données
GET : dans l'URL (par défaut, non sécure)
POST : dans le payload (plus sécure)

### Types de champs
input :
-> type="text" / "password" / ...
-> name : nom du champ envoyé au backend
label
-> for : associé à l'id du champ
select
-> name : nom du champ envoyé au backend
option (uniquement dans un select)
-> value : valeur sélectionnée envoyée au backend
textarea
-> name : nom du champ envoyé au backend
button
-> type="submit"
