## **[7] DEV BACK / SÉCURITÉ / OBJET / VERSIONNING**

### Les questions de cette section sont liées entre elles et concernent la CP 7.

#### Q7.1 - Quelles failles de sécurité majeures connais-tu ? Pour chacune d’elles, peux-tu les expliquer rapidement et proposer une solution pour s’en prémunir ?

> Ta réponse : 
> -les injections SQL, executer des requetes sql dans une bdd, pour s'en prémunir on peut échapper les données qui proviennent du client, et utiliser des requêtes préparés
>
> -attaques par force brute, tester tous les mots de passe jusqu'à trouver le bon pour s'en prémunir donner des consignes de sécurités à l'utilisateur (8 caractères + spéciaux ...) + double authentification et/ou CAPTCHA
> 
> CISEURF exploiter le session d'un utilisateur, pour d'en prémunir JWToken

> XSS injecter des script sur un site, et donc l'exécuter chez tous les utilisateurs, pour s'en prémunir CORS permet de sécuriser la communiquation server/client
&nbsp;

#### Q7.2 - Avec tes propres mots, comment expliquerais-tu à quoi sert l’héritage, en programmation orientée objet ?

> Ta réponse : l'héritage permet de créer une nouvelle classe à partir d'une classe existante.
> https://web.maths.unsw.edu.au/~lafaye/CCM/poo/heritage.htm

&nbsp;

#### Q7.3 - À quel moment est appelé (exécuté) le constructeur d’une classe ?

> Ta réponse : Lorsqu'on va créer un nouvel objet à partir de cette classe

&nbsp;

#### Q7.4 - Que veut dire ce développeur ? 

*“J’ai une 403 sur le endpoint de suppression user en prod mais pas en local”*

> Ta réponse : l'accès est non-authorisé sur la route qui permet de supprimer un utilisateur, sur le serveur de production , mais pas sur le serveur local

&nbsp;

#### Q7.5 - Peux tu donner une définition d’architecture dans le contexte du développement web ? 

> Ta réponse : Une architecture d'application décrit les modèles et les techniques utilisés pour concevoir et créer une application.
> Une architecture d'application comprend les services front-end et back-end.Le développement front-end concerne l'expérience utilisateur de l'application, tandis que le développement back-end permet de fournir l'accès aux données, aux services et à d'autres systèmes dont dépend l'application.

&nbsp;

#### Q7.6 - Qu’est-ce que le pattern MVC ? 

> Ta réponse : L’architecture MVC (modèle, vue et contrôleur), son principal intérêt est la séparation des concepts: les données (modèle), de l’affichage (vue) et des actions (contrôleur).

&nbsp;

---

[Une petite dernière pour la route ? Direction les compétences transversales](Transverse.md)