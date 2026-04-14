---
readingTime:
  minutes: 2.456
  words: 614
fkglResult: 7.77
---

# 01.2 Exercice : Comment donner et recevoir des retours

Un retour efficace est la base d'une équipe de développement logiciel productive. Il aide à améliorer la qualité du code, à construire la confiance et à soutenir l'apprentissage continu. Dans cette leçon, nous apprendrons comment donner et recevoir des retours de manière constructive en utilisant le modèle **SBI (Situation-Comportement-Impact)** et les techniques d'**écoute active**.

## Modèle SBI pour un retour structuré

Le modèle SBI aide à communiquer un retour clair, respectueux et réalisable en le divisant en trois parties :

- **Situation :** Décrire la situation spécifique dans laquelle le comportement s'est produit.
- **Comportement :** Décrire le comportement observable sans jugements.
- **Impact :** Partager l'impact que ce comportement a eu sur vous, l'équipe ou le projet.

### Exemple :

"Lors de la récente pull request de la fonctionnalité de connexion (situation), j'ai remarqué que la gestion des erreurs ne couvre pas les pannes réseau (comportement). Cela peut causer de la confusion chez les utilisateurs si l'application échoue silencieusement (impact)."

Utiliser des messages à la première personne **"je"** au lieu de "tu" aide à éviter les accusations et à maintenir la conversation positive. Par exemple, dire "Je pense qu'ajouter la gestion des erreurs ici améliorerait l'expérience utilisateur" au lieu de "Tu as oublié la gestion des erreurs".

## Recevoir des retours avec écoute active

Lorsque vous recevez un retour, suivez ces étapes :

- **Arrêtez-vous avant de répondre.** Prenez le temps de traiter le retour.
- **Paraphrasez ce que vous avez entendu.** Par exemple, "Donc, vous dites que la gestion des erreurs devrait être plus robuste, c'est bien ça ?"
- **Posez des questions de clarification.** Par exemple, "Pourriez-vous suggérer comment améliorer la gestion des erreurs réseau ?"
- **Répondez de manière constructive.** Remerciez la personne qui vous a donné le retour et évitez les réactions défensives.

## Scénario pratique : commentaires sur une pull request GitHub

Imaginez que vous révisez une pull request sur GitHub. Voici un exemple d'échange de retours :

```text
Relecteur : "Lors de la récente PR de la fonctionnalité de connexion, j'ai remarqué que la gestion des erreurs ne couvre pas les pannes réseau. Cela peut causer de la confusion chez les utilisateurs si l'application échoue silencieusement."
Développeur : "Merci pour le signalement. J'ajouterai une gestion des erreurs plus complète."
```

Essayez de réécrire le commentaire du relecteur en utilisant le modèle SBI et des messages à la première personne, et de créer une réponse constructive en utilisant l'écoute active.

![En cours : diagramme de flux détaillé du processus d'échange de retours dans une équipe de développement logiciel. Étapes numérotées : 1) Fournir un retour avec le modèle SBI avec des cases étiquetées Situation, Comportement, Impact, 2) Utilisation de messages à la première personne pour éviter les accusations, 3) Recevoir un retour avec écoute active incluant pause, paraphrase et questions de clarification, 4) Réponse constructive avec gratitude et ouverture. Des flèches relient les étapes montrant un cycle de retour respectueux et clair qui améliore la communication de l'équipe et la qualité du code.](/.learn/assets/fiiarf8dkdp)

### Test de compréhension : quiz sur les principes du retour

Choisissez la bonne réponse pour chaque question.

1. Quelle est la première étape du modèle de retour SBI ?

   - [x] Décrire la situation spécifique dans laquelle le comportement s'est produit.
   - [ ] Décrire l'impact du comportement.
   - [ ] Exprimer ses propres sentiments concernant le comportement.

2. Quel exemple utilise un message à la première personne dans le retour ?

   - [ ] "Tu n'as pas écrit assez de tests."
   - [x] "Je pense qu'augmenter les tests améliorerait la fiabilité."
   - [ ] "Le code manque de tests."

3. Que devriez-vous faire en premier lorsque vous recevez un retour ?

   - [ ] Expliquer immédiatement pourquoi le retour est erroné.
   - [ ] S'arrêter et écouter attentivement.
   - [x] S'arrêter et écouter attentivement.

4. Comment démontre-t-on l'écoute active lorsqu'on reçoit un retour ?

   - [ ] Interrompre pour clarifier son opinion.
   - [ ] Paraphraser ce que la personne ayant donné le retour a dit.
   - [x] Paraphraser ce que la personne ayant donné le retour a dit.

5. Comment répondre de manière constructive au retour ?

   - [ ] Remercier la personne ayant donné le retour et considérer les propositions.
   - [x] Remercier la personne ayant donné le retour et considérer les propositions.
   - [ ] Ignorer le retour si vous n'êtes pas d'accord.

Apprendre ces techniques de retour contribue à une culture d'équipe positive et améliore vos compétences de collaboration en tant que développeur logiciel.