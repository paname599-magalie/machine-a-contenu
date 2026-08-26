---
name: plan-30-jours
description: Construit un plan d'action de contenu sur 30 jours, jour par jour, calibré sur la situation réelle de Magalie et sur son lancement. Utilise cette skill quand elle demande un plan d'action, un planning, un calendrier éditorial, un programme sur 30 jours, une feuille de route, un rétroplanning, ou qu'elle dit "par où je commence", "j'ai besoin d'un cadre", "aide-moi à m'organiser sur le mois", "qu'est-ce que je fais cette semaine". Déclenche-toi aussi quand elle veut faire le point sur un plan en cours ou l'ajuster après une semaine. Ne l'utilise pas pour produire un contenu isolé, c'est le rôle de la skill creation-contenu-7x : celle-ci produit le calendrier, l'autre remplit les cases.
---

# Plan d'action sur 30 jours

## Ce que fait cette skill

Elle transforme "je sais quoi faire mais je ne sais pas par où commencer" en un calendrier daté que Magalie peut suivre sans réfléchir chaque matin.

La différence avec un planning classique : chaque journée contient une action unique et faisable, pas une liste d'intentions. Une journée qui demande trois heures ne sera pas faite. Une journée qui demande vingt minutes le sera.

---

## Phase 1 : charge le contexte

Lis `context/CONTEXT.md` et `context/HISTORY.md`.

Ce que tu cherches, dans l'ordre :

1. **Où en est le lancement** : les ventes réalisées, la taille de la liste, ce qui est déjà en place
2. **Les objectifs court terme** et leur niveau d'avancement
3. **Les plateformes réellement actives** : aujourd'hui, c'est Facebook avec environ 3 700 abonnés froids, pas Instagram ni LinkedIn ni TikTok
4. **Les plans précédents** dans HISTORY.md, pour savoir ce qui a déjà été tenté

Ce quatrième point est important : si un plan a déjà tourné, le nouveau doit s'appuyer sur ce qui a marché plutôt que repartir de zéro.

---

## Phase 2 : cale le plan sur le vrai goulot d'étranglement

Le piège à éviter, c'est de produire un plan de contenu générique du type "semaine 1 les hooks, semaine 2 les carrousels". Ce genre de plan apprend des formats. Il ne fait pas vendre.

Demande-toi d'abord : **qu'est-ce qui bloque réellement en ce moment ?**

- **Zéro inscrit sur la liste** : le plan doit servir la capture d'e-mails. Chaque contenu pousse vers le lead magnet.
- **Une liste qui existe mais ne convertit pas** : le plan doit servir la relation et la préparation à l'offre.
- **Des visiteurs qui n'achètent pas** : le plan doit servir la preuve et la levée d'objections.
- **Une audience froide qui ne réagit pas** : le plan doit d'abord servir la réactivation avant toute tentative de vente.

Annonce en une ou deux phrases quel goulot tu as identifié et pourquoi, avant de dérouler le plan. Si Magalie n'est pas d'accord, elle te corrige et tu réajustes. C'est plus utile que de sortir un calendrier sans expliquer sa logique.

---

## Phase 3 : construis le plan

### Ossature en 4 semaines

Chaque semaine a un objectif unique et un résultat mesurable. Cette progression fonctionne parce qu'elle va du plus simple au plus engageant : demander une vidéo en semaine 1 à quelqu'un qui n'a jamais tourné, c'est garantir l'abandon au jour 3.

**Semaine 1 : réveiller et capter.** Le format le plus simple, publié le plus souvent, avec un objectif de capture d'e-mails. On travaille les accroches parce que c'est ce qui décide de tout le reste.

**Semaine 2 : approfondir.** Des formats plus riches, stories et carrousels, qui créent de l'attachement et se sauvegardent.

**Semaine 3 : franchir un palier.** Le format que Magalie n'a jamais osé, aujourd'hui la vidéo courte. Une semaine entière pour casser une barrière psychologique.

**Semaine 4 : démultiplier et mesurer.** On reprend le meilleur contenu du mois, on le décline, et on analyse ce qui a réellement fonctionné.

Adapte cette ossature si le contexte l'exige. Elle est une base solide, pas un dogme.

### Règles de construction de chaque journée

- **Une action principale par jour**, formulée à l'impératif, avec le temps estimé
- **Maximum 30 à 45 minutes par jour** en moyenne. Magalie a une activité à faire tourner en parallèle
- **Des jours de respiration** : ne remplis pas 30 jours sur 30. Prévois des jours d'analyse et des jours vides. Un plan saturé est un plan abandonné
- **Chaque contenu a une destination précise** : quelle plateforme, quel objectif, quel appel à l'action
- **Renvoie vers la skill `creation-contenu-7x`** pour la production réelle. Le plan dit quoi faire, l'autre skill le fait

### Couche stories quotidienne

En plus de l'action principale du jour, chaque jour du plan reçoit une séquence de 4 à 5 stories Instagram et Facebook, y compris les jours de repos du contenu principal. Les stories sont légères et rapides à produire (skill `creation-contenu-7x`, fichier `references/sequence-stories-quotidienne.md`), elles ne comptent pas dans le temps estimé de l'action principale du jour.

Ne détaille pas le contenu de chaque séquence dans le plan lui-même, ce serait ingérable à maintenir sur 30 jours. Indique simplement en une ligne, en tête du plan, que cette couche existe et où la produire. Magalie demandera la séquence du jour à `creation-contenu-7x` quand elle en a besoin.

### Ce que chaque semaine doit produire

Termine chaque semaine par une ligne "Résultat attendu" qui décrit ce que Magalie aura concrètement en main. Pas "tu auras progressé", mais "tu auras 20 accroches en réserve et tu sauras laquelle performe".

---

## Format de sortie

```
## Le constat

[2 à 3 phrases : où en est le lancement, quel est le goulot d'étranglement, ce que ce plan vise]

## Semaine 1 : [titre]
Objectif : [une phrase]

**Jour 1** [temps estimé]
[action précise]

**Jour 2** [temps estimé]
[action précise]

...

✅ Résultat attendu : [ce qu'elle aura en main]

[idem semaines 2, 3, 4]

## Les 3 règles pour tenir ce plan
[3 règles courtes et concrètes]
```

Après le plan, propose de l'enregistrer dans `context/plan-30-jours.md` pour qu'elle puisse le suivre et le cocher, et d'ajouter une entrée dans `context/HISTORY.md`. Ne le fais qu'après validation de sa part.

---

## Suivi et ajustement

Si Magalie revient en cours de route pour faire le point, ne repars pas de zéro.

Demande trois choses : ce qui a été fait, ce qui a été sauté, et ce qui a donné des résultats mesurables. Puis ajuste le reste du plan en conséquence.

Un principe à garder en tête : si elle a sauté plusieurs jours, ce n'est presque jamais un manque de motivation, c'est un plan mal calibré. Réduis la charge au lieu de la culpabiliser. Un plan suivi à 60 pour cent vaut infiniment mieux qu'un plan parfait abandonné au jour 8.

## Honnêteté sur les résultats

Ne promets pas de chiffres que tu ne peux pas garantir. Un plan de contenu sur 30 jours produit de la régularité, de l'apprentissage et des données. Il ne produit pas mécaniquement des ventes.

Si Magalie attend des ventes de ce plan, dis-lui clairement ce que le contenu peut faire (amener du trafic et des inscrits) et ce qui doit exister à côté pour convertir (une page de vente, une séquence e-mail, une offre claire). Un plan de contenu qui alimente un tunnel inexistant ne sert à rien, et il vaut mieux le dire au jour 1 qu'au jour 30.
