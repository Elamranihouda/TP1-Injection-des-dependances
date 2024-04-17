## Activité Pratique N° 1- Injection des dépendances
### Partie 1 : Création des Interfaces et Implémentations
##### 1. Nous avons commencé par créer l'interface IDao qui définit une méthode getDate
##### 2. Ensuite, nous avons mis en place une implémentation de cette interface
##### 3. Par la suite, nous avons défini l'interface IMetier avec une méthode calcul
##### 4. Une implémentation de cette interface a été créée en utilisant le couplage faible

### Partie 2 : Injection des Dépendances
#### 5. Pour l'injection des dépendances, nous avons exploré différentes méthodes :
#### a. Par instanciation statique : Nous avons instancié manuellement les dépendances dans le code
#### b. Par instanciation dynamique : Nous avons créer un fichier deconfiguration "config.txt" dans lequel nous avons declaré les classes utilisées
#### c. En utilisant le Framework Spring : Nous avons utilisé Spring, un framework populaire pour le développement d'applications Java, pour gérer l'injection des dépendances de manière plus efficace. Nous avons exploré deux approches :

#### Version XML : En configurant les dépendances dans un fichier XML de configuration, décrivant les relations entre les différents composants de l'application.
#### Version Annotations : En utilisant les annotations fournies par Spring telles que @Autowired pour indiquer les dépendances à injecter directement dans le code source.

