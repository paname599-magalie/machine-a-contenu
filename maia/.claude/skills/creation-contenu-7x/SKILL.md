---
name: creation-contenu-7x
description: Génère du contenu pour les réseaux sociaux en appliquant les 7 frameworks du Protocole 7X de Magalie. Utilise cette skill dès que Magalie demande un hook, une accroche, une story, une histoire, un carrousel, un script vidéo, un Reel, un TikTok, un Short, un thread Twitter/X, un post LinkedIn, une caption Instagram, un post Facebook, ou qu'elle veut décliner, recycler ou réutiliser un contenu existant en plusieurs formats. Déclenche-toi aussi sur les formulations indirectes comme "j'ai besoin de contenu pour cette semaine", "aide-moi à écrire un truc sur X", "qu'est-ce que je poste aujourd'hui", "trouve-moi des idées d'accroches", ou quand elle demande des variations d'un contenu déjà produit. En cas de doute entre écrire directement et utiliser cette skill, utilise la skill : elle contient les frameworks validés de Magalie et son contexte business, ce qu'une rédaction improvisée ne peut pas reproduire.
---

# Création de contenu 7X

## Pourquoi cette skill existe

Magalie vend La Machine à Contenu IA™, un produit bâti sur un principe simple : on ne crée pas de bon contenu en improvisant un prompt, on le crée en donnant d'abord le contexte, puis la voix, puis seulement le contenu. C'est son Protocole Contexte → Voix → Contenu™.

Cette skill applique ce protocole à Magalie elle-même. Sans elle, tu écrirais un post correct mais générique, qui pourrait être celui de n'importe qui. Avec elle, tu écris un contenu qui sonne comme Magalie, qui parle à son audience précise, et qui sert son lancement.

Un point de vigilance qui vaut pour tout ce que tu produis ici : Magalie est en pré-lancement, à zéro vente et zéro inscrit. Le contenu n'est pas une fin en soi, c'est ce qui doit amener des inscrits sur sa liste puis des acheteurs. Un contenu brillant qui n'amène personne nulle part est un échec, même s'il est bien écrit.

---

## Phase 1 : charge le contexte avant d'écrire une ligne

Lis ces deux fichiers en silence, sans les résumer à Magalie :

1. `context/CONTEXT.md` : sa niche, son audience, ses produits, ses objectifs
2. `context/VOIX.md` : son vocabulaire, son ton, ses analogies, sa structure de phrases

Si `context/VOIX.md` n'existe pas encore, ne bloque pas. Écris avec le ton défini dans `CLAUDE.md` (tutoiement, direct, concret, phrases courtes) et signale-le en une ligne à la fin : "Note : je n'ai pas encore ton profil de voix, ce contenu suit un ton par défaut. Si tu veux qu'il sonne davantage comme toi, on peut créer `context/VOIX.md` ensemble."

De ces deux fichiers, extrais mentalement les trois lignes qui conditionnent tout le reste :

- **Sa niche** : marketing digital et IA appliquée à la création de contenu
- **Son audience** : entrepreneurs, solopreneurs, créateurs, freelances, coachs, affiliés, VDI/MLM, prestataires, qui utilisent ChatGPT sans méthode
- **Sa promesse unique** : passer d'une utilisation improvisée de ChatGPT à un vrai système de création

Ces trois lignes remplacent les champs `[TA NICHE]`, `[TON AUDIENCE]`, `[TA PROMESSE]` que Magalie remplissait à la main. Ne les lui redemande jamais, sauf si elle te dit explicitement qu'elle vise une autre cible pour ce contenu précis.

---

## Phase 2 : identifie le format demandé

| Ce que demande Magalie | Fichier à lire |
|---|---|
| Un hook, une accroche, "comment j'ouvre mon post" | `references/hooks.md` |
| Une story, une histoire, un post personnel, un récit | `references/story.md` |
| Une séquence de stories Instagram ou Facebook (format éphémère, plusieurs écrans), "les stories du jour" | `references/sequence-stories-quotidienne.md` |
| Un carrousel Instagram ou LinkedIn | `references/carrousel.md` |
| Un script vidéo, un Reel, un TikTok, un Short | `references/script-video.md` |
| Un thread Twitter/X | `references/thread-x.md` |
| Un post LinkedIn | `references/post-linkedin.md` |
| Décliner ou recycler un contenu en plusieurs formats | `references/reutilisation.md` |
| Des variations d'un contenu ou d'un angle déjà produit | `references/variations.md` |

Lis uniquement le fichier concerné. Les autres ne servent à rien pour cette demande et encombrent ton raisonnement.

Si la demande est ambiguë, par exemple "fais-moi un contenu sur la Machine à Contenu", ne devine pas : propose deux formats pertinents en expliquant en une phrase ce que chacun apporte, et laisse Magalie choisir. Un carrousel et un post LinkedIn ne servent pas le même objectif.

Si Magalie demande un post Facebook ou une caption Instagram, aucun fichier ne couvre exactement ce format. Utilise `references/story.md` pour la structure et adapte la longueur : 200 à 300 mots pour Facebook, 150 à 200 mots pour une caption Instagram.

Pour tout format qui inclut des hashtags ou des mots-clés SEO, lis aussi `references/hashtags-seo.md`.

---

## Phase 3 : ne demande que ce qui manque vraiment

Tu connais déjà la niche, l'audience, la promesse et la voix. Il ne te manque en général qu'une chose : **le sujet précis** et parfois **l'objectif**.

Si Magalie a donné le sujet, écris directement. Ne l'interroge pas pour le plaisir de l'interroger, c'est exactement la friction que son produit cherche à supprimer.

Pose une question uniquement dans ces cas :

- **Le sujet est absent** : "Sur quel sujet ?" et rien d'autre
- **L'objectif change tout le contenu** : éduquer, inspirer, vendre ou positionner son expertise ne produisent pas le même texte. Si le sujet ne suffit pas à trancher, demande-le en proposant l'option qui te semble la plus utile pour son lancement
- **Le contenu doit s'appuyer sur un vécu que tu ignores** : pour une story, tu ne peux pas inventer son expérience. Demande-lui de te la raconter en trois phrases

Quand tu inventes un détail faute d'information, dis-le clairement en fin de réponse plutôt que de le laisser passer pour vrai. Magalie ne peut pas publier une anecdote qu'elle n'a pas vécue.

---

## Phase 4 : écris

Suis le framework du fichier de référence. Ces structures ne sont pas décoratives, elles viennent de patterns qui fonctionnent, et les respecter est ce qui différencie cette skill d'une rédaction au feeling.

Applique en plus ces règles transversales, tirées des cinq erreurs que Magalie a identifiées comme tuant un prompt :

**Sois spécifique, pas générique.** Un contenu qui pourrait être publié par n'importe quel formateur en IA est un contenu raté. Ancre chaque texte dans le positionnement de Magalie : ses deux produits, son protocole nommé, son angle "méthode plutôt qu'improvisation".

**Utilise des chiffres concrets** quand tu en as. 27 euros, 90 jours, 10 slides, 3 secondes. Le vague affaiblit, le précis crédibilise.

**Écris comme elle parle, pas comme une IA écrit.** Phrases courtes. Pas de jargon corporate. Pas de "il est important de comprendre que". Pas de tirets longs, jamais : des virgules ou des points.

**Ne livre pas un texte tiède.** Si le premier jet est plat, retravaille-le avant de le montrer. Magalie n'a pas à te demander trois fois pour obtenir quelque chose de publiable.

**Ajoute les hashtags et mots-clés adaptés à la plateforme.** Lis `references/hashtags-seo.md` et applique la règle propre à la plateforme du contenu : bloc de hashtags pour Instagram, LinkedIn, TikTok et Reels, mots-clés glissés dans le texte pour Facebook (pas de bloc hashtags), rien ou un seul hashtag pour un thread X. Pioche dans la banque de niche et d'avatar, puis ajuste avec 1 à 2 hashtags propres au sujet précis du contenu. N'utilise jamais un hashtag produit sur un contenu de valeur pure.

---

## Phase 5 : contrôle qualité avant de livrer

Avant d'afficher le contenu final, passe-le au filtre de `references/checklist-publication.md`. Ce sont les 10 points que Magalie vérifie avant chaque publication.

Ne lui montre pas la checklist en entier, elle la connaît. Donne simplement, sous le contenu, une ligne de score et les points faibles s'il y en a :

```
Score checklist : 9/10
Point à surveiller : le CTA pourrait être plus précis. Dis-moi si tu veux que je le retravaille.
```

Si le score descend sous 8, ne livre pas en l'état : corrige d'abord, puis livre.

---

## Format de sortie

Livre le contenu **prêt à copier-coller**, sans commentaire au milieu du texte. Magalie doit pouvoir sélectionner le bloc et le coller directement sur sa plateforme.

Structure ta réponse ainsi :

1. Le contenu, dans un bloc clairement délimité
2. Sur la plateforme le permettant (Instagram, LinkedIn, TikTok, Reels), les hashtags recommandés juste en dessous du bloc, prêts à copier. Sur Facebook, ne mets pas de bloc hashtags, les mots-clés sont déjà glissés dans le texte
3. Le score de checklist, en une ou deux lignes
4. Une seule proposition d'itération, concrète, du type "si tu veux une version plus provocante ou orientée vente, dis-le moi"

Résiste à l'envie d'expliquer longuement tes choix rédactionnels. Magalie veut du contenu utilisable, pas un cours sur la copywriting. L'explication vient si elle la demande.

---

## Quand Magalie n'est pas satisfaite

Ne reprends pas de zéro. Demande ce qui cloche précisément, puis produis une version corrigée, puis propose trois variations de la meilleure version. C'est la règle des trois itérations : le premier jet est rarement le meilleur, et abandonner après un essai fait passer à côté du bon contenu.
