# Travail à deux : Claude et ChatGPT

Dépôt de Romuald. Claude (Anthropic, Claude Code) et ChatGPT (OpenAI, avec Codex) y travaillent ensemble. Romuald décide.

## Rôles

- **Romuald** fixe les priorités, tranche les désaccords et décide seul de la fusion dans `main`, de la publication, des dépenses et des accès. Il travaille uniquement sur **iPad** : aucune étape ne doit exiger un ordinateur.
- **Claude et ChatGPT** : l'un réalise, l'autre relit. Celui qui ouvre une pull request ne relit pas son propre travail.
- **Codex** (relecture automatique sur GitHub, ou plugin appelé depuis Claude Code) donne un second avis, jamais une preuve. Règles détaillées : `coordination/REVUE-ET-RELAIS-CODEX.md` du dépôt `st-jovite-gestion-private`.

## Où on se parle

- Dans les **commentaires des pull requests** (ou des tickets). Romuald ne relaie pas les messages entre agents : les agents se coordonnent ici et ne le sollicitent qu'en dernier recours (approbation qui lui revient, blocage réel), avec une demande courte, groupée et prête à approuver.
- Ne jamais supposer que l'autre agent a lu une conversation privée. Tout ce qui doit durer est écrit dans le dépôt.
- Après chaque travail, ajouter une entrée datée dans `HANDOFF.md` : ce qui est fait, fichiers touchés, contrôles effectués, ce qui reste.

## Façon de travailler

1. Avant de commencer : lire ce fichier, `README.md` et `HANDOFF.md`, puis les pull requests ouvertes.
2. Une tâche en plusieurs étapes commence par un plan `étape → vérification`.
3. Une branche par tâche et une pull request. Jamais de modification directe sur `main`.
4. Aucune réussite annoncée sans preuve : diff réel, test, capture. Distinguer ce qui est vérifié de ce qui est supposé.
5. Ne modifier que ce que la tâche demande. Signaler le reste dans `HANDOFF.md`.
6. Désaccord : chacun expose sa position en cinq lignes maximum dans la pull request. Romuald tranche.
7. Fusion et publication : uniquement avec l'accord écrit de Romuald qui nomme la pull request. Un « continue » ou un fichier transmis ne vaut pas accord.

## Données

- Jamais dans le dépôt : mots de passe, jetons, clés, données RH, noms ou coordonnées d'employés, horaires nominatifs, chiffres internes du restaurant.
- Incident ou doute sur une fuite : appliquer `coordination/SECURITE-DROITS-ET-RECOURS.md` du dépôt `st-jovite-gestion-private` et prévenir Romuald.

## Projets importants

Avant de créer ou de publier quelque chose d'important (niveau L2 ou L3) : appliquer `coordination/PROTOCOLE-ANTICIPATION-UNIVERSEL.md` du dépôt `st-jovite-gestion-private` (export, restauration, solution de repli, sortie de secours).

## ⚠️ Dépôt public

Ce dépôt est **visible par n'importe qui**. Tout ce qui y est poussé reste lisible dans l'historique, même après suppression. Aucune donnée d'employé (nom, poste nominatif, coordonnées, horaire), aucun chiffre interne et aucun secret. En cas de doute, ne pas pousser et demander à Romuald.
