![Booki](https://booki.mathisbarre.com/img/booki_banner.png)
### 
###
## Contexte
## _L’entreprise souhaite développer un site Internet qui permette aux usagers de trouver des hébergements et des activités dans la ville de leur choix._
### 
###
## Mission
- Créer la page d'accueil d'une agence de voyage en utilisant HTML et CSS
- Intégrer l'**interface responsive** du site
### Projet commencé le 28 mars 2024

### 
###
## Attendus
- Implémenter une interface responsive avec HTML et CSS
- Intégrer du contenu conformément à une **maquette** avec HTML et CSS
- **Versionner** son projet avec Git et Github
- Installer un **environnement de développement** front-end

### 
###
## Spécifications fonctionnelles

| Fonction | Description |
| ------ | ------ |
|**Fonction recherche**| _ Les usagers pourront **rechercher des hébergements dans la ville de leur choix**. |
|| _ Le champ de recherche est **un champ de saisie**, le texte doit donc pouvoir être édité par l’utilisateur.|
|  | _ Il faut **englober ce champ dans un formulaire**. La partie Recherche ne doit pas être fonctionnelle, il s’agit d’une première version pour valider l’interface. |
|||
|**Liens “Hébergements” et “Activités”**|**Les textes “Hébergements”** et **“Activités”**, situés dans l’en-tête, sont des liens. Ils doivent mener respectivement vers la section “Hébergements à Marseille” et **“Activités à Marseille”.|
|||
|**Cartes hébergements et activités**|_ **Chaque carte** d’hébergement ou d’activité **devra être cliquable** dans son intégralité (pas uniquement le titre).|
||_ Pour l’instant, les liens sont vides. On peut utiliser un attribut `href=”#”` pour simuler la présence d’un lien.|
|||
|**Filtres de recherche**|_ Les hébergements peuvent être filtrés par thématique, comme le budget ou l’ambiance.|
||_ Les filtres doivent changer de couleur au survol de la souris.|
||_ Les filtres ne doivent pas être fonctionnels - il s’agit juste d’une première version pour valider l’interface..|


### 
###
## Spécifications techniques

| Thème | Informations techniques |
| ------ | ------ |
|**Maquettes**|**Trois maquettes** ont été réalisées : **desktop, tablette et mobile**.|
|||
|**Breakpoints**|Nous avons convenu avec le designer UI d’utiliser 1024 px et 768 px :|
||>1024 px pour les écrans d’ordinateurs|
||=768 px pour les tablettes|
||et tout ce qui est en dessous de 768 pour les téléphones portables|
|||
|**Largeur min - max**|Pour éviter d’étirer la page web sur la largeur de façon excessive, il va falloir **déterminer une largeur maximum de 1440 px**. Au-delà, une marge blanche doit apparaître sur les côtés et le contenu doit se limiter à 1440 px de large. La largeur minimum est fixée à 320 px, en-deçà de cette largeur, le comportement n’est pas garanti.|
|||
|**Desktop first**|Il faut d’abord réaliser l’intégration pour les ordinateurs (autrement dit, en **desktop first**), puis les tablettes et enfin les téléphones. L’utilisation des **Media Queries nous permettra de réaliser l’intégration pour les différents supports**.|
|||
|**Bibliothèque d’icônes**|Les icônes proviennent de la bibliothèque [Font Awesome](https://docs.fontawesome.com/web/setup/get-started)|
|||
|**Couleurs**|Les couleurs de la charte sont le **bleu (#0065FC)**, **le bleu clair (#DEEBFF)** et le **gris** pour le **fond (#F2F2F2)**.|
|||
|**Police**|La police du site est **Raleway**. Nous pouvons passer par **Google Fonts** pour importer facilement cette police dans le code : https://fonts.google.com/specimen/Raleway.|
|||
|**Mise en page**|Il est recommandé d'utiliser **Flexbox**|
|||
|**Balises sémantiques**|Il est important d’**utiliser des balises sémantiques**, au minimum “header”, “nav”, “h1-h2-h3”, “main”, “section”, “article” et “footer”.|
|||
|**Validité du code**|Aucun IDE ou éditeur de code particulier n’est imposé pour le développement|
||Le **code** doit être **valide aux validateurs** W3C [HTML](https://validator.w3.org/)et [CSS](https://jigsaw.w3.org/css-validator/).|
||Le code HTML ne doit pas contenir de propriété CSS.|
||Lors du passage du desktop au mobile et à la tablette, **ne pas dupliquer le code** HTML (exception faite dans le formulaire avec le mot “Rechercher” et l’icône de la loupe).|
||**Privilégier l’utilisation des classes CSS** pour cibler un élément, plutôt que d’utiliser le nom de l’élément lui-même.|
||**Ne pas dupliquer des classes CSS inutilement**. Exemple : si 4 éléments sont identiques du point de vue de la mise en forme, alors utiliser une seule et même classe CSS, et non pas 4.|
|||
|**Compatibilité navigateurs**|La **maquette** doit être **compatible avec les dernières versions de Google Chrome et de Mozilla Firefox**. Il faudra tester la page web sur ces deux navigateurs.|
|||
|**Restrictions**|**Aucun framework** CSS (type BootStrap ou Tailwind CSS) ou préprocesseur CSS (type Sass ou Less) ne doit être utilisé.|
||**Aucun autre langage** ne doit être utilisé (comme JavaScript, par exemple).|



### 
###
## Technologies utilisées

HTML5 et CSS3 (avec flexbox)


### 
###
## Projet de base

- URL du repository : https://github.com/OpenClassrooms-Student-Center/booki-starter-code
- Maquettes du site : https://www.figma.com/file/r9YJyUkpVdrxzBBKGH7reY/Maquettes-Booki-(desktop%2C-mobile%2C-tablette)?type=design&node-id=3-0&mode=design&t=z1tnTE7Vf4NOnQZJ-0
- HOW TO MAKE CSS CARDS (W3) : https://www.w3schools.com/howto/howto_css_cards.asp
### 
###
## Installation

```sh
# Création du répertoire
mkdir projet2 - BOOKI
cd projet2 - BOOKI

# Configuration générale GITHUB
git config --global user.name "nicolasmorvant"
git config --global user.mail nicolas.morvant@tuta.io
    
# Configuration des éditeurs :
git config --global core.editor vim 
git config --global merge.tool vimdiff

# Récupération du projet
git clone https://github.com/OpenClassrooms-Student-Center/booki-starter-code
git remote set-url origin https://github.com/nicolasmorvant/booki.git
```

### 
###
## Réalisation

| Date | Réalisation |
| ------ | ------ |
| 28/03/2024 | Découpage de la maquette en HTML |
|||
| 30/04/2024 | Ajout de la maquette  |
| | Document disponible dans ```/docs``` |
|||
| | Intégration du header de la version desktop |
|||
||  Ajout du formulaire de recherche|
|||
||  Ajout des filtres|
|||
|||