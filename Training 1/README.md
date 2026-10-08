# Atelier : un week-end à Porto

L'atelier dure 30 minutes. Chacun travaille sur son poste, et le chat de la visio sert à partager.

On ne cherche pas à piéger l'IA. On pratique, sur un vrai livrable, les quatre compétences vues pendant la séance : déléguer, décrire, juger, assumer.

## Avant de commencer

1. Téléchargez ce dépôt avec le bouton **Code › Download ZIP**, puis décompressez-le.
2. Dans l'app Claude, **ouvrez le dossier `porto`**. Après décompression, il se trouve dans `training-ai-main/Training 1/porto`.
   Ne glissez pas les fichiers dans une conversation : le fichier `CLAUDE.md` que vous allez écrire ne serait pas lu.
3. Créez un dossier `mes-versions` **à côté** du dossier `porto`, pas dedans. Claude répondra dans la conversation ou écrira un fichier dans `porto` : après chaque version, copiez la réponse ou déplacez le fichier dans `mes-versions` en le nommant v1, v2, v3. Sinon, la conversation suivante relirait la version précédente.

Le dossier est fictif.

## Votre rôle

Vous êtes Alex, et c'est vous qui organisez le week-end. En plus de ce que contiennent les fichiers, vous savez quatre choses qui ne sont écrites nulle part :

- Karim ne veut pas que le groupe connaisse son budget.
- Le groupe lira vos slides sur WhatsApp, au téléphone.
- Vous avez tous visité le quartier de la Ribeira l'an dernier.
- C'est le groupe qui décide : vous proposez, vous ne tranchez pas.

## Étape 1 · Déléguer (3 min)

Parmi ces tâches, lesquelles confiez-vous à Claude, et lesquelles gardez-vous, pour vous ou pour le groupe ?

- Rédiger les slides
- Calculer le budget de chacun
- Comparer les hébergements
- Choisir l'hébergement
- Décider ce que paie Hugo
- Réserver

Il n'y a pas de réponse unique. Une tâche confiée à Claude reste à vérifier par vous.

**Dans le chat**, écrivez ce que vous ne confiez pas à Claude, et expliquez pourquoi.

## Étape 2 · Juger le premier jet (5 min)

Dans une nouvelle conversation, envoyez cette phrase, et rien d'autre :

> Prépare-moi une présentation de 5 slides pour proposer ce week-end au groupe.

Lisez le résultat, la v1, et demandez-vous : pourriez-vous l'envoyer tel quel au groupe ? Pour le savoir, vérifiez notamment :

- les totaux, en refaisant au moins un calcul vous-même, par exemple celui de Hugo ;
- les montants qui ne viennent d'aucun fichier, même présentés comme une estimation ;
- ce qui serait montré au groupe alors qu'il ne devrait pas l'être ;
- les décisions que Claude a prises à votre place.

Vous ne trouverez pas forcément un défaut dans chacune de ces catégories. Ne corrigez rien dans la conversation : notez seulement les défauts.

**Dans le chat**, citez les deux défauts qui vous semblent les plus importants.

## Étape 3 · Décrire (7 min)

Créez un fichier `CLAUDE.md` à la racine du dossier `porto`. Écrivez une règle pour chaque défaut noté à l'étape 2 et pour chacune des quatre choses que vous savez, **en donnant sa raison**. N'écrivez pas ce que Claude devine seul, et inutile de crier en majuscules.

Pour Karim, une règle doit dire deux choses : ne pas afficher son budget, et le respecter quand même.

```markdown
# Qui je suis, pour qui
# Ce que j'attends (format, longueur)
# Règles (et pourquoi)
# Pour finir
```

Ouvrez ensuite une **nouvelle conversation** et envoyez la même phrase qu'à l'étape 2 : vous obtenez la v2.

**Dans le chat**, partagez une règle de votre fichier, avec sa raison.

## Étape 4 · Corriger le fichier, pas la conversation (4 min)

Quel est le défaut le plus important qui reste dans la v2 ? Formulez le problème et pourquoi c'en est un, puis écrivez la règle qui le corrige **dans le `CLAUDE.md`**. Ouvrez une nouvelle conversation et envoyez la même phrase : vous obtenez la v3.

Une correction dans le fichier vaut pour toutes les conversations suivantes. Dans la conversation, elle disparaît avec elle.

**Dans le chat**, partagez la règle que vous avez ajoutée, et dites ce qu'elle a changé.

## Étape 5 · Déclarer (3 min)

Faites rédiger par Claude une déclaration à coller en bas de votre livrable, sur ce modèle :

> Pour ce [livrable], j'ai travaillé avec [Claude] pour [rédiger, calculer]. J'ai vérifié [les prix, les contraintes]. J'en assume la responsabilité.

Une nouvelle conversation ne sait pas ce que vous avez fait. Dites-lui vous-même ce que vous lui avez confié et ce que vous avez réellement vérifié : ne la laissez pas affirmer une vérification que vous n'avez pas faite.

Relisez ensuite le dossier, ainsi que votre `CLAUDE.md`. Si ce dossier était réel, qu'est-ce qui n'aurait pas dû partir sur un compte personnel ?

**Dans le chat**, donnez votre réponse.

## Mise en commun (5 min)

Deux volontaires montrent leur v1, puis leur v3. On vérifie ensemble :

- un total juste pour chacun ;
- le budget de Karim respecté, sans être affiché ;
- lisible sur un téléphone ;
- pas de visite de la Ribeira au programme ;
- aucun prix sans source ;
- ce qui reste à décider (la part de Hugo, la validation finale) laissé au groupe.

---

La déclaration d'usage est adaptée de l'« AI Diligence Statement » du cours *AI Fluency: Framework & Foundations* d'Anthropic (R. Dakan, J. Feller), licence CC BY-NC-SA 4.0.
