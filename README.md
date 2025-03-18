# PHP QCM
Ce repo a pour but de vous aider à maîtriser PHP. Il est structuré en plusieurs sections couvrant les fondamentaux du langage, les fonctions, la manipulation de fichiers, les bases de données et d'autres concepts avancés.

## Comment ça fonctionne ?

Chaque section correspond à une branche Git distincte. Pour répondre aux questions, vous devez vous placer sur la branche appropriée, ajouter vos réponses, puis soumettre.

### Forker le repo vers votre compte Github


### Cloner ensuite le repo
```bash
git clone https://github.com/[votre-username]/php-qcm
```

### Basculer sur la branche de la section à compléter
Avant d'ajouter vos réponses, assurez-vous d’être sur la bonne branche :
```bash
git checkout <nom-de-la-section> # Ex: 01-culture-generale
```

### Compléter les réponses
Dans chaque section concernée, ajoutez vos réponses :

### Committer et pousser vos modifications
```bash
git add .
git commit -m "Ajout des réponses pour [nom de la section]"
git push origin <nom-de-la-section>
```

## Structure des branches

| Branche                | Contenu                                      |
|------------------------|----------------------------------------------|
| `01-culture-generale`     | Questions générales sur PHP et les serveurs |
| `02-http-fondamentaux`    | Concepts liés au protocole HTTP et aux superglobales |
| `03-syntaxe-bases`       | Syntaxe de base et types de données         |
| `04-chaines-de-caracteres` | Manipulation des chaînes de caractères    |
| `05-tableaux`            | Travail avec les tableaux en PHP            |
| `06-fonctions`           | Déclaration et utilisation des fonctions    |
| `07-fichiers`           | Gestion des fichiers en PHP                 |
| `08-dates`              | Manipulation des dates et heures             |
| `09-erreurs`            | Gestion des erreurs et exceptions           |
| `10-base-de-donnees`    | Connexion et requêtes SQL en PHP            |
| `11-poo`                | Programmation Orientée Objet                |
| `12-php-avance`         | Concepts avancés : Composer, MVC, etc.       |
| `13-algorithmes`        | Exercices d’algorithmique en PHP            |
| `14-pratique`           | Cas pratiques et projets concrets           |
