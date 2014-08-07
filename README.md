# Jekyll Now

**Jekyll** est un générateur de site statique qui est parfait pour les blogs hébergés sur GitHub ([Repository Jekyll](https://github.com/jekyll/jekyll))

**Jekyll Now** facilite la création de votre blog Jekyll, en éliminant beaucoup de réglages amont.

- Vous n'avez pas besoin de toucher la ligne de commande
- Vous n'avez pas besoin d'installer/configurer ruby, rvm/rbenv, ruby gems :relaxed:
- Vous n'avez pas besoin d'installer des dépendances de runtime comme les processeurs markdown, Pygments, etc
- Si vous êtes sur Windows, ceci facilitera grandement l'installation de Jekyll
- C'est facile d'essayer, vous pouvez simplement effacer votre repository forké si vous n'aimez pas

En quelques minutes, vous aurez installé un blog minimal, responsive comme celui en-dessous vous laissant un peu de temps pour écrire des billets de blog épiques !

![Aperçu du Thème Jekyll Now](/images/jekyll-now-theme-screenshot.jpg "Jekyll Now Theme Screenshot")

## Démarrage Rapide

### Étape 1) Forkez "Jekyll Now" sur votre Repository Utilisateur

Forkez ce repo, puis renommez-le en votrenomutilisateur.github.io.

Votre blog Jekyll sera souvent visualisable instantanément sur  <http://votrenomutilisateurgithub.github.io> (si ce n'était pas le cas, vous pouvez le forcer à se construire en achevant l'étape 2)

![Étape 1](/images/step1.gif "Step 1")

### Étape 2) Personnalisez et regardez votre site

Entrez votre nom de site, la description, l'avatar et plein d'autres options en éditant le fichier _config.yml. Vous pouvez aussi aisément activer le suivi Google Analytics, des commentaires Disqus et quelques icônes sociales.

Produire une modification sur le fichier _config.yml (ou tout fichier dans votre repository) forcera GitHub Pages à reconstruire votre site avec jekyll. Votre site reconstruit sera visualisable quelques secondes plus tard sur <http://votrenomutilisateur.github.io>

> Il existe 3 façons différentes pour faire des modifications sur les fichiers de votre blog :

> 1. Éditer les fichiers dans votre nouveau repository  nomutilisateur.github.io à l'intérieur de votre navigateur directement sur GitHub.com (présenté en-dessous).
> 2. Utiliser un éditeur de contenu GitHub tiers, comme [Prose de Development Seed](http://prose.io). Il est optimisé pour fonctionner avec Jekyll et faciliter la production d'édition markdown, l'écriture de brouillons et le téléversement d'images.
> 3. Clonez votre repository sur votre machine et produire les mises à jour localement, puis les pousser vers votre repository GitHub.

![_config.yml](/images/config.png "_config.yml")
  
### Étape 3) Publier votre premier billet de blog

Éditez `/_posts/2014-3-3-Hello-World.md` pour publier votre premier billet de blog. Cette [Anti-sèche Markdown](http://www.jekyllnow.com/Markdown-Style-Guide/) pourra s'avérer pratique.

![Premier Post](/images/premier-post.png "Premier Post")

> Vous pouvez aussi ajouter des posts supplémentaires dans le navigateur sur Github.com ! Pressez simplemnet l'icône + dans  `/_posts/` pour créer un nouveau contenu. Assurez-vous juste d'inclure bloc [front-matter](http://jekyllrb.com/docs/frontmatter/) tout en haut de chaque post de blog et assurez-vous que le nom de fichier suive ce format : année-mois-jour-titre.md

## Développement local

1. Clonez localemnet votre fork `git clone git@github.com:votrenomutilisateur/votrenomutilisateur.github.io.git`
2. Installez Jekyll `gem install jekyll`
3. Installez les plug-ins que nous utilisons `gem install jemoji jekyll-sitemap`
4. Servez le site et regardez les modifications markup/sass  `jekyll serve --watch`
5. Visualisez votre site sur http://0.0.0.0:4000
6. Committez toutes les modifications et poussez tout sur la branche master de votre repository utilisateur GitHub. GitHub Pages reconstruira et servira votre site web.

## Moar!

J'ai créé un parcours plus détaillé, [**Build A Blog With Jekyll And GitHub Pages**](http://www.smashingmagazine.com/2014/08/01/build-blog-jekyll-github-pages/) sur le site web de Smashing Magazine. Regardez-le si vous aimeriez un parcours plus détaillé et quelque historique sur Jekyll. :metal:

Cela couvre : 

- Un parcours plus détaillé d'installation de votre blog Jekyll
- Les problèmes connus que vous pourriez rencontrer en utilisant Jekyll
- L'importation à partir de WordPress, en utilisant votre nom de domaine, et le blog dans votre éditeur favori
- Les thèmes dans Jekyll, avec des exemples de thèmes Liquid
- Un rapide aperçu des nouvelles fonctionnalités de Jekyll 2.0, y compris le support de Sass/Coffeescript et des Collections.

## Fonctionnalités de Jekyll Now

✓ Pas de ligne de commande. Un simple  _workflow-fork_, utilisant  GitHub.com pour créer, personnaliser et poster sur votre blog
✓ Thème de base totalement responsive et optimisé pour mobile  (**[Thème Demo](http://jekyllnow.com)**)  
✓ Support de Sass/Coffeescript utilisant Jekyll 2.0  
✓ Hébergement gratuit sur vos site d'utilisateur de Pages GitHub 
✓ Blog en Markdown
✓ Mise en valeur de la syntaxe
✓ Commentaires Disqus
✓ Intégration Google Analytics
✓ Icônes sociales SVG pour votre pied de page
✓ 3 requêtes http, y compris votre avatar
✓ Emoji dans le blog posts! :sparkling_heart: :sparkling_heart: :sparkling_heart:  

✘ Aucune installation de dépendances
✘ Aucun besoin de paramétrer un développement local
✘ Pas de plugins de configuration
✘ Aucun besoin de passer du temps sur la production de thèmes
✘ Plus de temps pour coder d'autres trucs  ... attendez ✓!  

## Questions ?

[Ouvrez une Issue](https://github.com/barryclark/jekyll-now/issues/new) et discutons !

## Recevoir mes nouveaux thèmes

Si vous aimeriez me faire savoir quand je sors un nouveau thème, [laissez-moi simplement votre e-mail pour les mises à jour](http://eepurl.com/XUZpT). Je suis en train de travailler actuellement sur un site portfolio de thèmes de hackers.

## Autres thèmes forkables

Vous pouvez utiliser le workflow [Quick Start](https://github.com/christopheducamp/jekyll-now##démarrage-rapide) avec d'autres thèmes qui sont paramétrés pour être forkés ! Voici quelques-uns de mes préférés :

- [Hyde](https://github.com/poole/hyde) par MDO
- [Lanyon](https://github.com/poole/lanyon) par MDO
- [mojombo.github.io](https://github.com/mojombo/mojombo.github.io) par Tom Preston-Werner
- [Left](https://github.com/holman/left) par Zach Holman

## Crédits

- [Jekyll](https://github.com/jekyll/jekyll) - Merci à ses créateurs, contributeurs et mainteneurs.
- [Icônes SVG](https://github.com/neilorangepeel/Free-Social-Icons) - Merci à Neil Orange Peel. Elles sont splendides. 
- [Solarized Light Pygments](https://gist.github.com/edwardhotchkiss/2005058) - Merci Edward.
- [Joel Glovier](http://joelglovier.com/writing/) - Superbes  articles sur Jekyll. J'ai utilisé le feed.xml de Joel dans ce repository.
- [David Furnes](https://github.com/dfurnes), [Jon Uy](https://github.com/jonuy), [Luke Patton](https://github.com/lkpttn) - Remerciements pour les révisions de design/code.

## Faites-vous Recruter comme Développeur Web 

Jetez un oeil à ma [newsletter gratuite web development](http://www.barryclark.co/newsletter) si vous êtes intéressés pour augmenter vos chances de trouver le job que vous voulez.
