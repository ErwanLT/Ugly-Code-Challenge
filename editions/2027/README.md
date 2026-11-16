# Éditions 2027

Bienvenue dans la saison 2027 de l'**Ugly Code Challenge**.

Cette saison regroupe les éditions organisées au cours de l'année 2027. Chaque édition propose un thème différent, avec ses propres contraintes, ses dates et son vote.

## Les éditions

| Édition | Thème | Ouverture | Clôture des soumissions | Vote | Vainqueur |
|---|---|---|---|---|---|
| [#001](./2027-01-ministere-des-excuses/) | Le Ministère des Excuses | 4 janvier 2027 | 28 février 2027 | 1er au 14 mars 2027 | À déterminer |

Chaque dossier d'édition contient un `README.md` détaillant :

- le contexte et la mission ;
- les exigences fonctionnelles ;
- les dates clés ;
- les modalités de vote.

## Organisation du dépôt

```text
editions/
└── 2027/
    ├── README.md                          # Ce fichier
    └── 2027-01-ministere-des-excuses/     # Édition #001
        ├── README.md                      # Sujet de l'édition
        └── candidates/                    # Participations (à créer)
            └── <identifiant>/             # Un dossier par candidat
                └── README.md              # Présentation de la solution
```

## Comment participer ?

1. Choisissez l'édition en cours dans le tableau ci-dessus.
2. Lisez son `README.md` et vérifiez les dates de soumission.
3. Forkez le dépôt et créez une branche dédiée.
4. Placez votre réalisation dans `editions/2027/<edition>/candidates/<identifiant>/`.
5. Ajoutez un `README.md` présentant votre solution, ses technologies et ses instructions d'exécution.
6. Ouvrez une Pull Request vers `main` avant la date limite.

Les règles complètes sont décrites dans [CONTRIBUTING.md](../../CONTRIBUTING.md) et le [CODE_OF_CONDUCT.md](../../CODE_OF_CONDUCT.md) s'applique à l'ensemble des échanges.

## Rappel

Le gagnant est le participant dont la Pull Request reçoit le plus de réactions 👍 pendant la période de vote.

**Make it work. Make it ugly. Make us laugh.**
