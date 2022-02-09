## Présentation du sujet

**1. Onboarding**

La première phase de l'application mobile à développer consiste à présenter un écran d'onboarding
à l'utilisateur lors du tout premier usage.

![](https://xdguru.b-cdn.net/wp-content/uploads/2019/01/Mobile-Onboarding-screens-templates.jpg)
Exemple d'onboarding: les images et le contenu ne sont pas importants, c'est le principe

Le travail qui est demandé est donc de développer une application mobile qui:

1 - Détecte s'il s'agit du tout premier usage de l'application, dans quel cas afficher l'onboarding
2 - Si l'utilisateur a déjà consulté les écrans d'onboarding alors aller directement sur l'écran d'authentification

**2. Authentification**

La phase d'authentification doit permettre de tester les deux scnéarios suivants:
- Authentification valide avec l'utilisateur `muser/mpassw0rd`
- Afficher le message "Ce compte est bloqué" pour l'utilisateur `muser02/mpassword`
- Pour tout autre login, afficher un message d'erreur

**3. News**

![](https://cdn.dribbble.com/users/1998175/screenshots/15193792/media/298264c1ce856398c313dde0398ba00c.jpg?compress=1&resize=1600x1200&vertical=top)

Cette 3e phase consiste à reproduire (le mieux possible) l'écran ci-dessus (Discover) en utilisant l'URL ci-après pour récupérer une liste de news.

- Science: https://inshortsapi.vercel.app/news?category=science
- Business: https://inshortsapi.vercel.app/news?category=business
- Sports: https://inshortsapi.vercel.app/news?category=sports
- Technology: https://inshortsapi.vercel.app/news?category=technology
- Startup: https://inshortsapi.vercel.app/news?category=startup
- Automobile: https://inshortsapi.vercel.app/news?category=automobile

L'objectif est donc :

- D'afficher une liste de news
- Reproduire une UI (sans nécessairement activer la partie Recherche)
- Avoir une navigation horizontale par catégories: Science, Business, Sports, Technology, Startup et Automobile

**4. Technologies**

Si aucune technologie ne vous a été imposée, les options sont les suivants:

- [ ] Flutter
- [ ] Android
- [ ] iOS

**5. Librables**

- Le lien vers le repo Github contenant le code source du projet
- Une vidéo présentant l'application fonctionnelle


