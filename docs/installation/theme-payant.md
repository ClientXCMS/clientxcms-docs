---
sidebar_position: 10
---

# Installer un thème payant

**CLIENTXCMS** Propose des thèmes payant qui crée un site vitrine en même temps que votre espace client. Après avoir acheté un thème, suivez cette page pour l'installer en quelques minutes.

## Téléchargement de l'archive & Upload de fichier
Connectez-vous sur votre espace client *clientxcms.com* et télécharger l'archive dans la section "Téléchargement"
![img](https://media.discordapp.net/attachments/475073153509490689/1040988629373304852/image.png)

L'archive contient 2 dossiers : `public` et `Theme` 

Le dossier `public` doit être upload dans le dossier `/public/Themes` pour que cela fasse `/public/Themes/Resi` et le dossier `Theme` doit être upload dans le dossier `/Themes/` de votre installation de CLIENTXCMS pour refaire `/Themes/Resi`


## Migrations
![img](https://media.discordapp.net/attachments/972877473643634688/1040715327782264983/unknown.png)

Le thème rajoute des tables de configurations spécifiques, Cette erreur apparait sur votre page en environnement de production, il faut donc migrer la base de données en changeant l'environnement en développement depuis votre fichier `.env` disponible à la racine.
Pour modifier l'environnement [cliquez ici](../developpers/environnement)
:::info Informations
Si ce fichier n'est pas affiché sur filezilla, WinSCP essayez de le créer avec un clique droit "Nouveau fichier" ".env", Il devrait vous l'afficher pour pouvoir l'éditer.
:::
Après avoir rechargé votre page, plus d'erreurs seront affichées et vous pourrez remettre votre environnement en production.

## Configurations
Vous pouvez configurer les liens vers vos réseaux sociaux, les liens pied de page et les différents composants de la page d'accueil.
![img](https://media.discordapp.net/attachments/882576437075394650/983110492082024498/unknown.png)
