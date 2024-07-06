## Activité Pratique N° 1- Injection des dépendances
### Partie 1 : Création des Interfaces et Implémentations
##### 1. Nous avons commencé par créer l'interface IDao qui définit une méthode getDate
<img width="530" alt="1" src="https://github.com/Elamranihouda/TP1-Injection-des-dependances/assets/96799465/bc4e2500-74cf-4859-bd78-4edcd845cef7">.
##### 2. Ensuite, nous avons mis en place une implémentation de cette interface.
<img width="483" alt="2" src="https://github.com/Elamranihouda/TP1-Injection-des-dependances/assets/96799465/c73bc064-e163-411b-8b22-14f07e2a45f1">.
##### 3. Par la suite, nous avons défini l'interface IMetier avec une méthode calcul
<img width="408" alt="3" src="https://github.com/Elamranihouda/TP1-Injection-des-dependances/assets/96799465/fdbbc38c-3ed5-45cc-a370-2076c447d444">.
##### 4. Une implémentation de cette interface a été créée en utilisant le couplage faible
<img width="506" alt="4" src="https://github.com/Elamranihouda/TP1-Injection-des-dependances/assets/96799465/3e852cf8-21c2-4050-a08c-ae1db0792dcc">.
### Partie 2 : Injection des Dépendances
#### 5. Pour l'injection des dépendances, nous avons exploré différentes méthodes :
#### a. Par instanciation statique : Nous avons instancié manuellement les dépendances dans le code
<img width="468" alt="5" src="https://github.com/Elamranihouda/TP1-Injection-des-dependances/assets/96799465/038e9c3e-c9d3-4f88-a79b-22efc07d7321">.
#### b. Par instanciation dynamique : Nous avons créer un fichier deconfiguration "config.txt" dans lequel nous avons declaré les classes utilisées
<img width="415" alt="52" src="https://github.com/Elamranihouda/TP1-Injection-des-dependances/assets/96799465/894d5199-a6b2-437a-a8b9-8bc14bb76e41">.
<img width="544" alt="522" src="https://github.com/Elamranihouda/TP1-Injection-des-dependances/assets/96799465/26778e90-90b6-4cfb-bb79-d7d10b626e14">
#### c. En utilisant le Framework Spring : Nous avons utilisé Spring, un framework populaire pour le développement d'applications Java, pour gérer l'injection des dépendances de manière plus efficace. Nous avons exploré deux approches :

##### - Version XML : En configurant les dépendances dans un fichier XML de configuration, décrivant les relations entre les différents composants de l'application.
<img width="604" alt="xml" src="https://github.com/Elamranihouda/TP1-Injection-des-dependances/assets/96799465/23b7a08b-c7bd-45a0-ba4c-17bd38d1ad9a">
<img width="740" alt="61" src="https://github.com/Elamranihouda/TP1-Injection-des-dependances/assets/96799465/5c88029b-0e64-4852-941f-60a3c120e6cb">.

##### - Version Annotations : En utilisant les annotations fournies par Spring telles que @Autowired pour indiquer les dépendances à injecter directement dans le code source.
<img width="416" alt="dao" src="https://github.com/Elamranihouda/TP1-Injection-des-dependances/assets/96799465/7b152501-b9bf-4bb8-b106-b86c98a08b54">
<img width="506" alt="metier" src="https://github.com/Elamranihouda/TP1-Injection-des-dependances/assets/96799465/7eb824ca-ea66-4d62-9549-a938caee6eb0">
<img width="704" alt="62" src="https://github.com/Elamranihouda/TP1-Injection-des-dependances/assets/96799465/206d85b2-4f94-404f-8617-c92c64f45e4c">

