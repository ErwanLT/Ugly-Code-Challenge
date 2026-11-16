# Édition #001 — Le Ministère des Excuses
![Static Badge](https://img.shields.io/badge/DU-4%20janvier-green)
![Static Badge](https://img.shields.io/badge/AU-15%20mars-green)

## Le contexte

Un déploiement vient de planter en production.

Le client attend des explications. Le chef de projet est en réunion. Le DevOps a mystérieusement disparu.

Le Ministère des Excuses de Déploiement est votre dernier recours.

## Votre mission

Développer un générateur d'excuses capable de transformer un incident technique en communication professionnelle.

Votre programme doit accepter les informations d'un incident et produire une excuse cohérente avec la situation.

## Exemple d'entrée

```json
{
  "service": "payment-api",
  "environment": "production",
  "error": "DatabaseConnectionTimeout",
  "severity": "CRITICAL",
  "customerImpact": true
}
```

## Exemple de résultat

```json
{
  "incidentId": "INC-2027-001",
  "excuse": "Notre base de données a décidé de méditer.",
  "severity": "CRITICAL",
  "customerMessage": "Nos équipes sont mobilisées.",
  "resolution": "Redémarrage des équipes de support."
}
```

## Exigences fonctionnelles

Votre solution doit :

- Accepter les informations d'un incident.
- Générer une excuse en rapport avec l'erreur.
- Adapter le discours au niveau de gravité.
- Fournir un message destiné au client.
- Proposer une résolution, même si elle est parfaitement absurde.
- Retourner un résultat structuré.
- Gérer les entrées invalides.

Les exemples ci-dessus sont indicatifs. Vous êtes libres de choisir le format de votre application.

## Liberté technique

Aucune restriction !

Java, Kotlin, JavaScript, TypeScript, Python, Rust, Go, C, COBOL, Brainfuck...

Spring Boot, Quarkus, React, Angular, Vue, Express, Flask...

API REST, CLI, application desktop, site web, bot...

Tout est autorisé, tant que votre réalisation fonctionne et peut être présentée.

## Les dates

- Ouverture : 4 janvier 2027.
- Date limite de soumission : 28 février 2027 à 23 h 59.
- Vote : du 1er au 14 mars 2027.
- Résultat : 15 mars 2027.

## Comment participer ?

1. Forkez le dépôt et créez une branche dédiée.
2. Placez votre réalisation dans `editions/2027/2027-01-ministere-des-excuses/candidates/<identifiant>/`.
3. Ajoutez un `README.md` présentant votre solution et ses instructions d'exécution.
4. Ouvrez une Pull Request vers `main` avant la date limite.

Le détail des règles se trouve dans [CONTRIBUTING.md](../../../CONTRIBUTING.md).

## Comment gagner ?

La Pull Request ayant obtenu le plus de réactions 👍 à la clôture des votes remporte cette édition.

Bonne chance. Et surtout, ne déployez pas ça en production.