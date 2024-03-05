---
title: How to Join
layout: html
---

# Rejoindre la Webring

Êtes-vous un-e auteur-trice francophone de Fiction Interactive ou un-e grand-e joueur-euse de FI avec une présence sur le web ? Aimerez-vous faire partager la FI à un plus grand public et être liés à d'autres membres de la communauté ?

Cette webring {JE SAIS PAS QUOI METTRE, ON VERRA}

## Ajoutez-vous à la liste de membres

Si vous voulez être inclu-e dans cette webrin, nous aurons besoin des informations suivantes :

- un <b>slug</b> unique : un mot descriptif pour vous identifiez dans la webring
- votre <b>page web</b> : votre site perso ou page itch.io, n'importe où vous parlez de FI
- le <b>nom</b> de votre page web
- (optionel) si vous être un-e auteur-rice de FI

### Via Github

Ajouter les informations nécessaires à la <a href="{{site.github_repo_url}}/blob/main/_data/members.csv">liste de membres</a> sur GitHub (lien here + PULL REQUEST).

### Via ??

Si pas de GitHub, utiliser une autre manière?


## Ajoutez le Widget sur votre page

Dès que vous êtes ajouté-e sur la liste de membres, vous pouvez ajouter le widget sur votre page person pour faire marcher la webring. Le widgets contient trois liens: la personne avant vous sur la liste, la personne après, et cette page.

- **{{'/VOTRE-SLUG/next'|absolute_url}}** (next)
- **{{'/VOTRE-SLUG/previous'|absolute_url}}** 
- **{{'/'|absolute_url}}** 

### Example widgets

Example:

```html
    <div id="webring" style="border-style: double; border-width: 2px; padding: 0.5em; max-width: 400px; text-align: center;">
        A member of the <a href="https://fiction-interactive-wr.netlify.app/ ">Webring FI FR</a>
        <br>
        <a href="https://fiction-interactive-wr.netlify.app/SLUG/previous">Previous</a> - <a href="https://fiction-interactive-wr.netlify.app/SLUG/next">Next</a>
    </div>
```
