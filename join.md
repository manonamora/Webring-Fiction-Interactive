---
title: Rejoindre le Webring
layout: html
---
Vous être un(e) auteur(rice) francophone de Fiction Interactive ou un(e) grand(e) joueur(euse) de FI avec une présence sur le web‎ ? Un(e) streamer(euse) sur Twitch ou un(e) essayiste‎ ? 
Aimeriez-vous faire partager la FI à un plus grand public et être liés à d'autres membres de la communauté‎ ?

<center>
## Rejoignez le Webring‎ !

Seulement deux étapes simples‎ !
</center>

### Ajoutez-vous à la liste de membres

Si vous voulez être inclu-e dans cet webring, nous avons besoin des informations suivantes‎ :

- un <b>slug</b> unique‎ : un mot descriptif pour vous identifier dans le webring
- votre <b>page web</b>‎ : votre site perso ou page itch.io, n'importe où vous parlez de FI
- le <b>nom</b> de votre page web
- (optionel) si vous être un(e) auteur(rice) de FI

#### Via Github

Ajouter les informations précédents dans une nouvelle ligne sur la <a href="{{site.github_repo_url}}/blob/main/_data/members.csv">liste de membres</a> dans le Répo Github. Pour faire ceci, <b>FORK</b>-ez le répo, éditez le fichier concerné, et créez une <b>PULL REQUEST</b>.
Un administrateur vérifiera les informations avant de vous ajouter sur la liste.

#### Via GoogleSheet

Si vous n'utilisez pas Github, vous pouvez ajouter les informations nécessaires dans une nouvelle ligne sur ce <a href="https://docs.google.com/spreadsheets/d/1LlywgB4e2XxwNeCvz0FrKyh2DCr24YIHnwcxETIps-A/edit?usp=sharing">GoogleSheet</a>.
Un administrateur vérifiera les informations avant de vous ajouter sur la liste.

<!-- Est-ce qu'on fait aussi un email? -->

### Ajoutez le Widget sur votre page

Dès que votre lien est actif sur la liste de membres, vous pouvez ajouter le widget nécessaire pour faire marcher le webring sur la page web que vous nous avez communiquée.
Le widget contient trois liens: celui rendant sur le site de la personne avant vous sur la liste, celui pour la personne après vous, et ce site.

- **{{'/VOTRE-SLUG/next'|absolute_url}}** (suivant)
- **{{'/VOTRE-SLUG/previous'|absolute_url}}** (précédent)
- **{{'/'|absolute_url}}** (ici)

Changez <b>VOTRE-SLUG</b> par le slug vous correspondant.

#### Exemples de widgets

Exemple 1:

```html
    <div id="webring" style="border-style: double; border-width: 2px; padding: 0.5em; max-width: 400px; text-align: center;">
        Membre de la <a href="https://fiction-interactive-wr.netlify.app/">Webring FI FR</a>
        <br>
        <a href="https://fiction-interactive-wr.netlify.app/VOTRE-SLUG/previous">Previous</a> - <a href="https://fiction-interactive-wr.netlify.app/VOTRE-SLUG/next">Next</a>
    </div>
```
<!-- Ce serait cool si on pouvait avoir des boutons pour la page.-->

<footer><nav>
<a href='/'>Accueil</a><br>
</nav></footer>
