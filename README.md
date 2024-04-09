# HOW TO AUTOMATED ADD-COMMIT-PUSH

Il s'agit d'une methode facile pour automatisé ses push en fin de journée si vous etes aussi tete en l'air que moi 

## Installation

Téléchargez ce code et ouvrez le , dans le fichier index.bat , vous devez faire les modifications suivante : 

```bash
git add .
git commit -m "YOUR_COMMIT_MESSAGE %DATE%"
git push  origin YOUR_BRANCH

```

## Usage

```bash
Ouvrez le Planificateur de tâches : Recherchez le Planificateur de tâches dans le menu Démarrer et ouvrez-le.

Créez une tâche : Cliquez sur Créer une tâche dans le volet de droite. Donnez un nom à votre tâche, choisissez Exécuter que l'utilisateur est connecté ou non, et configurez-le pour exécuter votre script batch. Sous l'onglet Déclencheurs, cliquez sur Nouveau et configurez-le pour qu'il se déclenche à l'heure souhaitée chaque jour.

Action : Sous l'onglet Actions, ajoutez une nouvelle action pour démarrer un programme, et sélectionnez votre script batch.
```

```bash
Notes Importantes :
    Authentification Git : Assurez-vous que votre système peut pousser vers votre dépôt sans intervention manuelle. Cela peut nécessiter la configuration de l'authentification par clé SSH ou l'utilisation d'un gestionnaire de credentials pour Git.
    Sécurité : Gardez à l'esprit les implications de sécurité de laisser un script avoir accès à vos dépôts Git.
    L'automatisation de ces tâches peut vous faire gagner du temps et assurer une certaine régularité dans vos engagements Git, mais utilisez-la judicieusement, surtout sur des projets partagés où des commits automatiques peuvent perturber le flux de travail de l'équipe.
```
## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.


## License
OPEN  SOURCE