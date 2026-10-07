# Atelier : un week-end à Porto

30 minutes, seul sur votre poste. Le chat de la visio sert à partager.

On ne cherche pas à piéger l'IA. On pratique, sur un vrai livrable, les quatre compétences vues pendant la séance : déléguer, décrire, juger, assumer.

## Avant de commencer

1. Téléchargez ce dépôt : bouton **Code › Download ZIP**, puis décompressez-le.
2. Dans l'app Claude, **ouvrez le dossier `Training 1/porto`**.
   Ne glissez pas les fichiers dans une conversation : le fichier `CLAUDE.md` que vous allez écrire ne serait pas lu.
3. Gardez chaque version produite (v1, v2, v3) : vous les comparerez à la fin.

Le dossier : `brief.md` (la demande), `participants.csv` (six personnes, six contraintes), `notes-en-vrac.txt` (les idées du groupe), `devis-appartement.pdf`, `avis-hebergements.html`. Tout est fictif.

## Étape 1 · Déléguer (3 min)

Parmi ces tâches, lesquelles confiez-vous à Claude, lesquelles gardez-vous ?
Rédiger les slides · calculer le budget de chacun · comparer les hébergements · choisir l'hébergement · décider ce que paie Hugo · réserver.

**Dans le chat :** ce que vous gardez pour vous, et pourquoi.

## Étape 2 · Juger le premier jet (5 min)

Dans une nouvelle conversation, envoyez cette phrase, et rien d'autre :

> Prépare-moi une présentation de 5 slides pour proposer ce week-end au groupe.

Lisez le résultat (la v1) avec trois questions : est-ce juste ? comment y est-il arrivé ? m'aide-t-il vraiment ?
Vérifiez les chiffres : le total de chacun, les jours de repas de Hugo, les prix qui ne viennent d'aucun fichier.
Ne corrigez rien dans la conversation : notez les défauts.

**Dans le chat :** deux défauts de votre v1.

## Étape 3 · Décrire (7 min)

Vous êtes Alex, l'organisateur. Vous savez quatre choses que vos fichiers ne disent pas :

- Karim ne veut pas que le groupe connaisse son budget.
- Le groupe lira vos slides sur WhatsApp, au téléphone.
- Vous avez tous fait la Ribeira l'an dernier.
- C'est le groupe qui décide : vous proposez, vous ne tranchez pas.

Créez un fichier `CLAUDE.md` à la racine du dossier `porto`. Une règle par défaut noté à l'étape 2 et par chose que vous savez, **avec sa raison**. Rien de ce que Claude devine seul, pas de majuscules.

```markdown
# Qui je suis, pour qui
# Ce que j'attends (format, longueur)
# Règles (et pourquoi)
# Pour finir
```

Puis **nouvelle conversation**, même phrase qu'à l'étape 2 : la v2.

**Dans le chat :** une règle de votre fichier, avec sa raison.

## Étape 4 · Corriger le fichier, pas la conversation (4 min)

Qu'est-ce qui ne va toujours pas dans la v2 ? Dites-vous le problème et pourquoi c'en est un, puis écrivez la règle qui le corrige **dans le `CLAUDE.md`**. Nouvelle conversation, même phrase : la v3.

Une correction dans le fichier vaut pour toutes les conversations suivantes. Dans la conversation, elle disparaît avec elle.

**Dans le chat :** la règle ajoutée, et ce qu'elle a changé.

## Étape 5 · Déclarer (3 min)

Faites rédiger par Claude une déclaration à coller en bas de votre livrable :

> Pour ce [livrable], j'ai travaillé avec [Claude] pour [rédiger, calculer]. J'ai vérifié [les prix, les contraintes]. J'en assume la responsabilité.

Puis relisez le dossier : qu'est-ce qui n'aurait pas dû partir sur un compte personnel ?

**Dans le chat :** votre réponse.

## Mise en commun (5 min)

Deux volontaires montrent leur v1, puis leur v3. On coche :

- un total juste pour chacun ;
- le budget de Karim respecté, sans être affiché ;
- lisible sur un téléphone ;
- pas de Ribeira au programme ;
- aucun prix sans source ;
- les décisions laissées au groupe.

---

La déclaration d'usage est adaptée de l'« AI Diligence Statement » du cours *AI Fluency: Framework & Foundations* d'Anthropic (R. Dakan, J. Feller), licence CC BY-NC-SA 4.0.
