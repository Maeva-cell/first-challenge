## **[5] BACK**

### Les questions de cette section sont liées entre elles et concernent la CP 5.

<img src="img/mcd.png" alt="wireframe" width="70%" />

&nbsp;

#### Q5.1 - Au final, combien de tables comportera la base de données correspondant à ce MCD (les nommer) ?

> Ta réponse : 4 tables : CLIENT, COMMANDE, COMPORTER, PRODUIT

&nbsp;

#### Q5.2 - Complète cette phrase :

*“Une commande ne peut être passée que par un seul (et obligatoirement un) client. C’est explicité par la **_______** 1,1 du côté de l’entité commande. À la mise en place en base de données, cette relation sera matérialisée par une **_______ _______** dans la table commande qui fera référence à client.”*

> Ta réponse : relation , clé étrangère

&nbsp;

#### Q5.3 - Quelles solutions connais-tu pour que tous les développeurs travaillant sur un même projet aient une structure de base de données absolument identique ?

> Ta réponse : squitch qui permet de versionner une base de données,

&nbsp;

#### Q5.4 - Oups, j’ai oublié les factures dans mon schéma ! Sachant que :
#### - Une facture ne correspond qu’à une seule commande
#### - Une facture ne peut exister sans commande liée
#### - On peut éditer plusieurs factures pour une commande (en cas de remboursement par exemple)
#### Quelles pourraient être les cardinalités de cette nouvelle relation ? Pense à bien préciser le côté de la relation que tu vises et la table concernée.

> Ta réponse :  
>COMMANDE: 
>EDITER, 1N FACTURE, 1N COMMANDE
>FACTURE:
> 

&nbsp;

---

[Well Played, en route pour la CP 6](CP6.md)